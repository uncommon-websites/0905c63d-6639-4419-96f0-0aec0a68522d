<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Clarity first",
			description: "We help cut through noise and complexity, focusing on what truly matters for your growth and decisions."
		},
		{
			title: "Reflection drives action",
			description: "Structured thinking creates better outcomes. We turn daily reflection into momentum and measurable progress."
		},
		{
			title: "Built for builders",
			description: "Designed specifically for founders and ambitious professionals who move fast and think faster."
		}
	];
</script>

<SecondaryHero
	title="Clarity for ambitious minds"
	subtitle="Where reflection turns into action"
	imageSrc="/generated/image-a-founder-sits-thoughtfully-at-a-clean-m.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started with a simple belief: founders and high-performing professionals deserve better tools for personal growth. While the market is flooded with generic coaching solutions, we chose to build something different.",
		"Our AI-driven reflection and action framework captures the essence of what makes great coaching work. We focus on structured thinking, actionable insights, and meaningful progress that compounds over time.",
		"From day one, we've asked ourselves: 'Does this actually help people grow?' This question guides every feature we build and every interaction we design. We're not chasing quick wins—we're building lasting transformation.",
		"We believe that clarity leads to better decisions, and better decisions create more fulfilling lives. Our platform helps ambitious minds turn reflection into action, one insight at a time."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet the founder."
	subtitle="Building the future of personal development"
	stakeholders={[
		{
			name: "Louis Morgner",
			position: "Founder",
			bio: "Passionate about helping founders and high-performing professionals unlock their potential through structured reflection and actionable insights.",
			image: "/generated/image-professional-headshot-of-a-young-male-en.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Turn thinking into action"
	subtitle="Start with 5 minutes a day"
	description="Join ambitious founders who've made structured reflection their daily practice. Experience how AI-driven coaching helps you cut through mental noise and focus on what matters most."
	imageSrc="/generated/image-a-professional-founder-smiling-thoughtfu.webp"
/>
