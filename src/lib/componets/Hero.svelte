<script>
    import EmailForm from './EmailForm.svelte';
</script>

<div class="text-center mb-16">
    <div class="bg-gradient-to-r from-[#1DB954] to-[#1ed760] text-transparent bg-clip-text">
        <h1 class="text-6xl font-bold mb-4">Build Better Habits Together</h1>
    </div>
    <p class="text-2xl text-gray-300 mb-12">Transform your daily routines with community-driven habit building</p>
    
    <div class="flex justify-center gap-4 mb-12">
        <button class="flex items-center gap-2 px-6 py-3 bg-black border border-gray-700 rounded-full hover:border-[#1DB954] transition-all">
            <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Download_on_the_App_Store_Badge.svg" alt="App Store" class="h-8">
            <span class="text-sm">Coming Soon</span>
        </button>
        <button class="flex items-center gap-2 px-6 py-3 bg-black border border-gray-700 rounded-full hover:border-[#1DB954] transition-all">
            <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Play Store" class="h-8">
            <span class="text-sm">Coming Soon</span>
        </button>
    </div>
    
    <EmailForm />
</div>