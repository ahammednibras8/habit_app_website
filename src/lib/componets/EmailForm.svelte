<script>
    let email = '';
    let feedback = '';
    
    function handleSubmit() {
        console.log('Email submitted:', email);
        console.log('Feedback:', feedback);
        email = '';
        feedback = '';
    }
</script>

<form on:submit|preventDefault={handleSubmit} class="max-w-xl mx-auto space-y-4">
    <div class="flex gap-2">
        <input
            type="email"
            bind:value={email}
            placeholder="Enter your email for early access"
            class="flex-1 px-6 py-3 rounded-full bg-gray-900 text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-[#1DB954] border border-gray-800"
            required
        />
        <button type="submit" class="px-8 py-3 bg-[#1DB954] rounded-full hover:bg-[#1ed760] transition-colors font-semibold">
            Get Early Access
        </button>
    </div>
    <textarea
        bind:value={feedback}
        placeholder="Share what features you'd love to see (optional)"
        class="w-full px-6 py-3 rounded-xl bg-gray-900 text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-[#1DB954] border border-gray-800 h-24 resize-none"
    ></textarea>
</form>