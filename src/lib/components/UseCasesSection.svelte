<script>
  const useCases = [
    {
      type: "Business Coach",
      problem: "Spending 40+ hours weekly on 1:1 calls, turning away clients",
      solution: "Digital clone handles initial consultations and follow-up questions",
      result: "Scaled from 20 to 200+ clients without adding team members"
    },
    {
      type: "Fitness Coach",
      problem: "Clients need support outside of scheduled sessions",
      solution: "24/7 AI mentor provides form tips, motivation, and nutrition guidance",
      result: "95% client retention, 3x revenue growth in 6 months"
    },
    {
      type: "Career Mentor",
      problem: "Can't respond to every LinkedIn DM from job seekers",
      solution: "Clone answers common questions about resume tips and interview prep",
      result: "Helped 1,000+ people while reclaiming 15 hours per week"
    },
    {
      type: "Podcast Host",
      problem: "Audience asks great questions but no time to engage individually",
      solution: "Digital clone continues conversations from podcast episodes",
      result: "10x audience engagement, deeper community connection"
    },
    {
      type: "Course Creator",
      problem: "Students need ongoing support after course completion",
      solution: "AI provides personalized guidance based on course material",
      result: "Higher completion rates, more 5-star reviews, premium pricing"
    },
    {
      type: "Consultant",
      problem: "Clients have questions between meetings, slowing project momentum",
      solution: "Clone answers technical questions using past project knowledge",
      result: "Faster project delivery, happier clients, more referrals"
    }
  ];
</script>

<section id="use-cases" class="py-20 px-6 md:px-12 border-t border-gray-300">
  <div class="flex flex-col md:flex-row">
    <!-- Left Column -->
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Use Cases</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        Real coaches. Real results. Real impact at scale.
      </p>
    </div>

    <!-- Right Column -->
    <div class="w-full md:w-3/4">
      <div class="mb-12">
        <p class="text-lg font-medium text-gray-700 leading-relaxed max-w-2xl">
          From business coaches to fitness experts, Delphi AI helps professionals scale their wisdom without sacrificing authenticity or burning out.
        </p>
      </div>

      <div class="space-y-8">
        {#each useCases as useCase}
          <div class="border-l-4 border-primary-500 pl-6 py-2 hover:border-primary-600 transition-colors">
            <h3 class="font-bold text-lg mb-2">{useCase.type}</h3>
            <div class="space-y-2 text-sm">
              <p class="text-gray-600"><span class="font-semibold text-gray-900">Challenge:</span> {useCase.problem}</p>
              <p class="text-gray-600"><span class="font-semibold text-gray-900">Solution:</span> {useCase.solution}</p>
              <p class="text-primary-700 font-medium"><span class="font-semibold">Result:</span> {useCase.result}</p>
            </div>
          </div>
        {/each}
      </div>

      <div class="mt-12 p-8 bg-gray-900 text-white">
        <h3 class="text-xl font-bold mb-4">Where coaching meets cloning—with trust at the core</h3>
        <p class="text-gray-300 leading-relaxed">
          We're not trying to replace you. We're replicating your mindset so more people can benefit, at scale. Your thoughts, your voice, your method—preserved and interactive.
        </p>
      </div>
    </div>
  </div>
</section>
