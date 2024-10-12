<script>
	import LargeHeader from "../../components/typography/LargeHeader.svelte";
	import MediumHeader from "../../components/typography/MediumHeader.svelte";
	import Paragraph from "../../components/typography/Paragraph.svelte";

</script>
<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>

<main>

	<LargeHeader>Julia</LargeHeader>
	<Paragraph>Bringing privacy back to the users.</Paragraph>

	<MediumHeader>Our Mission</MediumHeader>
	<Paragraph>There are plenty of chat apps out there. If you try any of them, pretty much the first thing they do is ask you for your phone number. The next thing is to import your contacts.</Paragraph>
	<Paragraph>This is all well and good, as it's reasonable to expect that if you send someone sms texts, you may also want to send them AR filtered snaps. The problem though is now you have duplicate lists of contacts to manage, and you're discoverable. Maybe you didn't want to delete your aunt's contact info, but maybe you didn't need her being able to find you on noplace.</Paragraph>
	<Paragraph>I didn't much care about this, but then in 2021 the US Supreme Court decided that people could text you no matter how they got your phone number. And even then it didn't matter until this year when the US presidential election decided I needed to get more messages from my affiliated party than a rejected incel (more on this later).</Paragraph>
	<Paragraph>Email's been ruined for years. Now my phone number's ruined.</Paragraph>
	<Paragraph>I'm old enough to remember when "You've got mail" was exciting. I wanted an app that tried to do that. Where if anyone wanted to find me, they couldn't, and I didn't have to feel bad about not connecting with them.</Paragraph>
	<Paragraph>That's the idea behind juliaswitch. Only connect with people that you want to connect with. Revoke that connection at any time, and they can't find you again (goodbye rejected incels).</Paragraph>

	
</main>

<style>
	main {
		margin-top: 15px;
		text-align: center;
	}

	@media screen and (max-width: 1080px) {
		main {
			margin: 0px 20px;
		}
	}
</style>