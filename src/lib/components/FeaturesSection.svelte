<script>
  const features = [
    {
      title: "Authentic Voice Cloning",
      description: "Your digital clone sounds like you, thinks like you, and answers like you. Trained on your unique style, frameworks, and expertise."
    },
    {
      title: "24/7 Availability",
      description: "Respond to DMs, emails, and client questions automatically. Your wisdom is always accessible, even when you're offline."
    },
    {
      title: "Personalized at Scale",
      description: "Offer tailored guidance to thousands without sacrificing quality. Each interaction feels one-on-one, but you're reaching everyone."
    },
    {
      title: "Instant Setup",
      description: "Upload your content, train your clone, and go live. No coding required—just your voice, ready to scale in minutes."
    },
    {
      title: "Real-Time Analytics",
      description: "See who's engaging, what they're learning, and where they need more support. Built-in feedback loops make your clone smarter every day."
    },
    {
      title: "Knowledge Preservation",
      description: "Capture and scale your expertise forever. Your insights reach more minds without adding more hours to your calendar."
    }
  ];
</script>

<section id="features" class="py-20 px-6 md:px-12 border-t border-gray-300">
  <div class="flex flex-col md:flex-row">
    <!-- Left Column -->
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Features</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        Scale yourself without burning out. Your voice, your knowledge, multiplied.
      </p>
    </div>

    <!-- Right Column -->
    <div class="w-full md:w-3/4">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        {#each features as feature}
          <div class="group cursor-default hover:transform hover:scale-[1.02] transition-all duration-300">
            <div class="bg-gray-50 p-6 h-full border border-gray-200 hover:border-primary-400 hover:shadow-lg transition-all duration-300">
              <h3 class="font-bold text-lg mb-3 text-gray-900">{feature.title}</h3>
              <p class="text-sm leading-relaxed text-gray-600">{feature.description}</p>
            </div>
          </div>
        {/each}
      </div>

      <div class="mt-12 p-8 bg-gradient-to-br from-primary-50 to-primary-100 border border-primary-200">
        <p class="text-lg font-medium mb-4">Built by founders who know the cost of doing it all alone.</p>
        <p class="text-sm text-gray-700">Designed for authenticity—your clone only says what you'd say. Grows with you—from 1:1 to 1:10,000.</p>
      </div>
    </div>
  </div>
</section>
