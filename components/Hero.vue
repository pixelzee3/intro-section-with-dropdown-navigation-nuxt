<template>
  <div>
    <picture>
      <source
        srcset="/images/image-hero-desktop.png"
        media="(min-width: 1024px)"
      />
      <img
        class="w-full"
        src="/images/image-hero-mobile.png"
        alt="A man working on a computer."
      />
    </picture>
    <Container>
      <article class="pt-10 text-center">
        <h1 class="font-bold text-4xl text-almost-black">Make remote work</h1>
        <Paragraph class="mt-4">
          Get your team in sync, no matter your location. Streamline processes,
          create team rituals, and watch productivity soar.
        </Paragraph>
      </article>
    </Container>
  </div>
</template>
