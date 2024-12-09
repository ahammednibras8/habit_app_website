<script>
    import FeatureCard from './FeatureCard.svelte';

    const features = [
        {
            title: 'Community Features',
            emoji: '🤝',
            items: [
                'Follow and get inspired by others\' routines',
                'Join group challenges',
                'Build habits together with friends'
            ]
        },
        {
            title: 'Smart Tracking',
            emoji: '📊',
            items: [
                'Visual progress insights',
                'Streak tracking',
                'Smart reminders'
            ]
        },
        {
            title: 'Gamification',
            emoji: '🏆',
            items: [
                'Earn badges and rewards',
                'Level up your consistency',
                'Complete milestones'
            ]
        }
    ];
</script>

<div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 mb-16">
    {#each features as feature}
        <FeatureCard {...feature} />
    {/each}
</div>