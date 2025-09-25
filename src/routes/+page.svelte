<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconLightbulb from "~icons/lucide/lightbulb";
	import IconPresentationChart from "~icons/lucide/presentation";
	import IconMessageSquare from "~icons/lucide/message-square";
	import IconEye from "~icons/lucide/eye";
	import IconTarget from "~icons/lucide/target";
	import IconTrendingUp from "~icons/lucide/trending-up";
</script>

<CenteredTextOnlyHero
	title="Turn your startup story into investor gold"
	subtitle="We help frontier founders craft compelling narratives that attract funding and customers, transforming scattered ideas into a cohesive worldview that drives growth."
	imageSrc="/generated/image-a-modern-interior-space-featuring-a-grou.webp"
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
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Turn scattered ideas into investor-ready narrative"
	subtitle="Strategic features designed specifically for frontier founders who need to articulate their vision and attract funding through compelling storytelling"
	features={[
		{
			title: "Worldview development",
			description: "Transform disconnected concepts into a cohesive company worldview that defines your unique market position and attracts both investors and customers.",
			icon: IconLightbulb
		},
		{
			title: "Investor narrative framework",
			description: "Craft compelling funding stories that clearly communicate your vision, traction, and market opportunity to secure the capital you need to grow.",
			icon: IconPresentationChart
		},
		{
			title: "Consistent messaging system",
			description: "Eliminate scattered communications with a unified narrative framework that ensures every touchpoint reinforces your core story and value proposition.",
			icon: IconMessageSquare
		},
		{
			title: "Vision articulation tools",
			description: "Develop clear, compelling language that helps you confidently communicate your company's future to stakeholders, customers, and team members.",
			icon: IconEye
		},
		{
			title: "Market differentiation strategy", 
			description: "Define what makes your approach unique in a crowded market through strategic narrative positioning that sets you apart from competitors.",
			icon: IconTarget
		},
		{
			title: "Narrative evolution guidance",
			description: "Adapt your story as your company grows with frameworks that help you refine messaging while maintaining consistency across all communications.",
			icon: IconTrendingUp
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
