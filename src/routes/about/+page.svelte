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
			title: "Innovation",
			description: "Constantly challenging the status quo to create better solutions."
		},
		{
			title: "Integrity",
			description: "Building trust through transparent actions and honest communication."
		},
		{
			title: "Impact",
			description: "Measuring our success by the positive change we create for our clients."
		}
	];
</script>

<SecondaryHero
	title="Stories that move markets"
	subtitle="Build a narrative investors believe in"
	imageSrc="/generated/image-a-founder-strategist-sits-at-a-large-woo.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"Most early-stage founders have a product, a pitch deck, and a vision. But what they often don't have is a coherent narrative that makes it all make sense—to investors, to customers, and even to their own team. Native started because we've lived this reality. Founder Jihad spent years watching talented frontier founders lose vital funding or fail to gain traction—not because the idea wasn't good, but because the story wasn't clear.",
		"We've turned that frustration into a focused approach. Native helps founders craft a compelling narrative that aligns worldview, product, and go-to-market into a single, powerful foundation. We aren't an agency. We're a strategic partner with founder-market fit—fluent in the nuances of early-stage tech and deeply embedded in the world of ambitious, frontier founders shaping what's next. Think of us as your narrative co-founder.",
		"Now, we're on a mission to raise the narrative standard for early-stage companies. Our goal is simple: make sure every great idea gets the clarity it deserves. Whether you're raising your first round or gearing up to launch, Native helps you build a story investors believe and customers remember. We're just getting started—and so are you."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Our team."
	subtitle="Your partners in innovation."
	stakeholders={[
		{
			name: "Alex Morgan",
			position: "Founder & CEO",
			bio: "Started the company with a vision to transform the industry through innovative solutions.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Jamie Chen",
			position: "Chief Design Officer",
			bio: "Award-winning designer with a passion for creating intuitive and beautiful experiences.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Taylor Wright",
			position: "Head of Engineering",
			bio: "Technology enthusiast focused on building scalable systems that make a difference.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by the best."
	subtitle="Point Nine, TSIC and others"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to collaborate?"
	subtitle="Let's create something amazing"
	description="Join the companies already leveraging our expertise to transform their digital presence and achieve their business goals."
/>
