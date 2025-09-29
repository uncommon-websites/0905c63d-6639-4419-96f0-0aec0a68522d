<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";

	// Icons
	import IconBrain from "~icons/lucide/brain";
	import IconTarget from "~icons/lucide/target";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconCompass from "~icons/lucide/compass";
	import IconActivity from "~icons/lucide/activity";
	import IconUsers from "~icons/lucide/users";
</script>

<Hero
	title="Think clearly. Act intentionally."
	subtitle="Structured reflection that drives real progress."
	imageSrc="/generated/image-a-professional-entrepreneur-working-inte.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/airtable.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Sharma",
			position: "CEO & Co-founder",
			company: "CloudBridge Labs",
			quote:
				"The structured reflection framework saved me 8 hours per week that I was spending in unproductive self-doubt cycles. In 3 months, I made clearer strategic decisions that increased our revenue by 40%. The AI-driven insights helped me identify blind spots I'd been missing for years.",
			image: "/generated/image-professional-headshot-of-priya-sharma-an.webp"
		},
		{
			name: "Marcus Chen",
			position: "Founder",
			company: "GreenTech Innovations",
			quote:
				"Before this platform, I was burning out making the same mental loops without progress. The actionable insights reduced my decision paralysis by 70% and helped me pivot our product strategy 6 months earlier than I would have otherwise. That early pivot saved us $200K in development costs.",
			image: "/generated/image-professional-headshot-of-marcus-chen-an-.webp"
		},
		{
			name: "Elena Rodriguez",
			position: "Co-founder & CTO",
			company: "DataFlow Solutions",
			quote:
				"The reflection framework transformed how I approach leadership challenges. I went from spending 15+ hours per week overthinking team dynamics to having clear action plans in under 2 hours. My team satisfaction scores improved by 35% in just 4 months because I became a more intentional leader.",
			image: "/generated/image-professional-headshot-of-elena-rodriguez.webp"
		}
	]}
/>

<Features
	title="AI-powered coaching designed for founders"
	subtitle="Transform scattered thoughts into clear action plans with structured reflection that drives measurable growth."
	features={[
		{
			title: "Smart reflection framework",
			description: "AI guides you through structured reflection sessions that turn overwhelming decisions into clear priorities. Built specifically for the complexity of startup leadership.",
			icon: IconBrain
		},
		{
			title: "Actionable insights engine",
			description: "Transform reflection into concrete next steps with AI that understands founder challenges. Get personalized action plans that move you forward, not just feel-good advice.",
			icon: IconTarget
		},
		{
			title: "Growth pattern recognition",
			description: "Identify what's actually driving your progress with AI that spots patterns across your decisions and outcomes. See the invisible threads connecting your wins.",
			icon: IconTrendingUp
		},
		{
			title: "Decision clarity system",
			description: "Cut through decision paralysis with structured frameworks that help you think clearly under pressure. Make confident choices when the stakes are high.",
			icon: IconCompass
		},
		{
			title: "Momentum tracking",
			description: "Maintain forward progress with intelligent check-ins that keep you accountable to your growth. Never lose sight of what matters when everything feels urgent.",
			icon: IconActivity
		},
		{
			title: "Founder-specific scenarios",
			description: "Navigate hiring, fundraising, product decisions, and team challenges with guidance tailored to startup realities. Not generic coaching, but startup-specific wisdom.",
			icon: IconUsers
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
