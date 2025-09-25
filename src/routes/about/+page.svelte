<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Patient first",
			description: "Every approval we accelerate means faster access to critical treatments for patients who need them most."
		},
		{
			title: "Efficiency",
			description: "Streamlining complex healthcare workflows so providers can focus on care, not paperwork."
		},
		{
			title: "Reliability",
			description: "Healthcare decisions depend on accuracy and speed—we deliver both with unwavering consistency."
		}
	];
</script>

<SecondaryHero
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Ready to streamline your authorizations?"
	subtitle="Transform your workflow today"
	description="Join the specialty clinics already reducing prior authorization delays and improving patient outcomes. See how our platform can accelerate your approval process."
	imageSrc="/generated/image-a-healthcare-administrator-sitting-at-a-.webp"
/>
