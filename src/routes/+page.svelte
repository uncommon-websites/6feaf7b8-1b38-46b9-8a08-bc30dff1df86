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
	import IconSmartphone from "~icons/lucide/smartphone";
	import IconDatabase from "~icons/lucide/database";
	import IconZap from "~icons/lucide/zap";
	import IconRocket from "~icons/lucide/rocket";
	import IconBarChart from "~icons/lucide/bar-chart-3";
</script>

<Hero
	title="Turn inaccessible knowledge into instant field support"
	subtitle="AI-powered mobile guidance that gives your technicians the answers they need, exactly when they need them."
	imageSrc="/generated/image-a-field-technician-in-sturdy-workwear-st.webp"
	centered={false}
/>
<LogoScroller
	label="Trusted by field service leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/servicenow.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/siemens.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/honeywell.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/se.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Frontline captures decades of operational knowledge and delivers it instantly to field technicians through mobile AI guidance. When a technician faces a complex repair, they get step-by-step instructions, troubleshooting help, and expert answers in real-time, transforming inaccessible manuals and tribal knowledge into actionable field support that reduces downtime and accelerates training."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "Operations Manager",
			company: "Summit HVAC Services",
			quote:
				"Frontline cut our technician onboarding time from 6 weeks to 9 days. New hires are confident in the field immediately, and our first-time fix rate jumped 42% in just three months.",
			image: "/generated/image-a-professional-hispanic-woman-who-is-an-.webp"
		},
		{
			name: "Marcus Williams",
			position: "Field Service Director",
			company: "Elevate Industrial Solutions",
			quote:
				"We eliminated 18 hours per week of support calls by giving technicians instant answers at their fingertips. The ROI was clear within 60 days—reduced downtime alone saved us $230K annually.",
			image: "/generated/image-a-professional-black-man-who-is-a-field-.webp"
		},
		{
			name: "Jennifer Chen",
			position: "VP of Operations",
			company: "Precision Electrical Services",
			quote:
				"Our callback rate dropped from 23% to 9% within the first quarter. Technicians solve complex issues on the first visit because they have expert knowledge in their pocket.",
			image: "/generated/image-a-professional-asian-woman-who-is-a-vp-o.webp"
		}
	]}
/>

<Features
	title="Everything your technicians need, right in their pocket"
	subtitle="Transform inaccessible knowledge into instant answers that keep your field team moving forward"
	features={[
		{
			title: "Instant AI answers",
			description:
				"Get accurate solutions in seconds, not hours. Your technicians tap into AI-powered guidance that understands context and delivers exactly what they need to complete the job.",
			icon: IconBrain
		},
		{
			title: "Mobile-first access",
			description:
				"Work where the work happens. Our intuitive mobile interface puts your entire knowledge base in every technician's pocket, accessible even in the harshest field conditions.",
			icon: IconSmartphone
		},
		{
			title: "Operational knowledge capture",
			description:
				"Turn tribal knowledge into organizational intelligence. Automatically capture insights from every repair, building a smarter system that learns from your team's expertise.",
			icon: IconDatabase
		},
		{
			title: "Real-time guidance",
			description:
				"Never feel stuck on a job again. Step-by-step instructions and visual aids guide technicians through complex repairs, reducing errors and building confidence.",
			icon: IconZap
		},
		{
			title: "Instant deployment",
			description:
				"Go live in hours, not months. Skip the lengthy training programs and complicated rollouts with our plug-and-play mobile solution that works from day one.",
			icon: IconRocket
		},
		{
			title: "Performance intelligence",
			description:
				"See what's working and what needs attention. Track resolution times, identify knowledge gaps, and measure ROI with actionable insights that drive continuous improvement.",
			icon: IconBarChart
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to transform your field operations?"
	subtitle="See results in days, not months"
	description="Join operations leaders who've already cut onboarding time by 75% and boosted first-time fix rates by 42%. Get a personalized demo and see how Frontline delivers instant mobile guidance that works from day one."
	imageSrc="/generated/image-a-confident-field-technician-stands-in-a.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Book your demo",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to our team",
			variant: "secondary"
		}
	]}
/>
