<script>
	import GitHubIcon from '$lib/icons/socials/github.svelte';
	import EmailIcon from '$lib/icons/socials/email.svelte';
	import DiscordIcon from '$lib/icons/socials/discord.svelte';
	import RedditIcon from '$lib/icons/socials/reddit.svelte';
	import XIcon from '$lib/icons/socials/x.svelte';
	import InstagramIcon from '$lib/icons/socials/instagram.svelte';
	import YoutubeIcon from '$lib/icons/socials/youtube.svelte';
	import FacebookIcon from '$lib/icons/socials/facebook.svelte';
	import TikTokIcon from '$lib/icons/socials/tiktok.svelte';
	import BlueskyIcon from '$lib/icons/socials/bluesky.svelte';
	import TelegramIcon from '$lib/icons/socials/telegram.svelte';
	import RSSIcon from '$lib/icons/rss.svelte';
	import LinkedinIcon from '$lib/icons/socials/linkedin.svelte';
	import MediumIcon from '$lib/icons/socials/medium.svelte';
</script>

<div class="socials">
	<a
		href="https://discord.langx.io"
		target="_blank"
		rel="noopener noreferrer"
		title="Join our Discord server"
	>
		<DiscordIcon />
	</a>
	<a
		href="https://reddit.com/r/langx"
		target="_blank"
		rel="noopener noreferrer"
		title="Join our Subreddit"
	>
		<RedditIcon />
	</a>
	<a href="https://x.com/langx_io" target="_blank" rel="noopener noreferrer" title="See our X Page">
		<XIcon />
	</a>
	<a
		href="https://bsky.app/profile/langx.io"
		target="_blank"
		rel="noopener noreferrer"
		title="See our BlueSky Page"
	>
		<BlueskyIcon />
	</a>
	<a
		href="https://t.me/langxapp"
		target="_blank"
		rel="noopener noreferrer"
		title="Join our Telegram Channel"
	>
		<TelegramIcon />
	</a>
	<a
		href="https://www.facebook.com/langxapp"
		target="_blank"
		rel="noopener noreferrer"
		title="See our Facebook Page"
	>
		<FacebookIcon />
	</a>
	<a
		href="https://tiktok.com/@langXapp"
		target="_blank"
		rel="noopener noreferrer"
		title="See our TikTok Page"
	>
		<TikTokIcon />
	</a>
	<a
		href="https://instagram.com/langxapp"
		target="_blank"
		rel="noopener noreferrer"
		title="See our Instagram Page"
	>
		<InstagramIcon />
	</a>
	<a
		href="https://www.youtube.com/@langxapp"
		target="_blank"
		rel="noopener noreferrer"
		title="See our YouTube Channel"
	>
		<YoutubeIcon />
	</a>
	<a
		href="https://github.com/langx"
		target="_blank"
		rel="noopener noreferrer"
		title="See our GitHub Page"
	>
		<GitHubIcon />
	</a>
	<a
		href="https://blog.langx.io"
		target="_blank"
		rel="noopener noreferrer"
		title="See our Medium Blog Page"
	>
		<MediumIcon />
	</a>
	<a
		href="https://www.linkedin.com/company/new-chapter-technology-limited-liability-company"
		target="_blank"
		rel="noopener noreferrer"
		title="See our Linkedin Page"
	>
		<LinkedinIcon />
	</a>
	<a href="/rss.xml" target="_blank" rel="noopener noreferrer" title="Subscribe to my RSS Feed">
		<RSSIcon />
	</a>
	<a href="mailto:hi@langx.io" target="_blank" rel="noopener noreferrer" title="Send an email">
		<EmailIcon />
	</a>
</div>

<style lang="scss">
	@import '../../scss/breakpoints.scss';
	.socials {
		display: flex;
		align-items: center;
		gap: 20px;
		flex-wrap: wrap;
		justify-content: center;

		a {
			transition: all 0.2s ease-in-out;
			width: 24px;
			color: var(--color--text);
			fill: var(--color--text);

			&:hover {
				color: var(--color--text);
				fill: var(--color--text);
				filter: drop-shadow(0px 0px 3px var(--color--text-shade));
			}
		}
	}
</style>
