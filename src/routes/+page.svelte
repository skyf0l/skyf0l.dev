<script lang="ts">
	const link =
		'border-b border-accent/60 transition-colors hover:border-accent hover:text-accent focus-visible:border-accent focus-visible:text-accent focus-visible:outline-2 focus-visible:outline-offset-4 focus-visible:outline-accent';
</script>

<svelte:head>
	<title>Skyf0l</title>
	<meta name="description" content="Skyf0l" />
</svelte:head>

<main class="flex min-h-dvh items-center justify-center px-(--pad-x) py-12">
	<div class="flex w-full max-w-[56.25rem] flex-col gap-(--gap-stack)">
		<div
			class="text-eyebrow text-fog/40 flex items-baseline justify-between gap-3 font-mono uppercase"
		>
			<span class="flex items-center gap-2">
				<span
					aria-hidden="true"
					class="animate-blink-slow bg-signal size-[7px] rounded-full shadow-[0_0_8px_var(--color-signal)]"
				></span>
				Online
			</span>
		</div>

		<div class="border-fog/15 flex flex-wrap items-baseline gap-[0.2em] border-y py-(--pad-frame)">
			<span aria-hidden="true" class="text-prompt text-fog/35 font-mono">&gt;</span>

			<h1 class="font-display text-wordmark">Skyf0l<span class="text-accent">.</span></h1>

			<span
				aria-hidden="true"
				class="animate-blink bg-accent ml-[calc(var(--text-wordmark)*0.06)] inline-block h-[calc(var(--text-wordmark)*0.29)] w-[calc(var(--text-wordmark)*0.16)] self-center"
			></span>
		</div>

		<footer class="flex flex-wrap items-baseline justify-between gap-3">
			<nav
				aria-label="Elsewhere"
				class="text-nav flex flex-wrap gap-(--gap-nav) font-mono uppercase"
			>
				<a class={link} href="https://github.com/skyf0l" target="_blank" rel="noopener noreferrer">
					GitHub
				</a>
				<a
					class={link}
					href="https://www.linkedin.com/in/tom-rorato"
					target="_blank"
					rel="noopener noreferrer"
				>
					LinkedIn
				</a>
				<a class={link} href="mailto:tom@rorato.dev">Email</a>
			</nav>
		</footer>
	</div>
</main>
