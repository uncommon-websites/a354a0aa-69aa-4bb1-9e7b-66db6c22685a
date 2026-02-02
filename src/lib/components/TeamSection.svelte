<script>
  const team = [
    {
      name: "Thilo",
      role: "Co-Founder & CEO",
      bio: "Experienced the crushing loneliness of being a solo founder. Built Delphi AI to solve scalable mentorship access at massive scale—so no founder has to go it alone.",
      image: "/generated/image-professional-portrait-of-a-thoughtful-fo-1770064642191-0.webp",
      linkedin: "#",
      twitter: "#"
    }
  ];
</script>

<section id="team" class="py-20 px-6 md:px-12 border-t border-gray-300">
  <div class="flex flex-col md:flex-row">
    <!-- Left Column -->
    <div class="w-full md:w-1/4 pr-8 mb-12 md:mb-0">
      <h2 class="text-xl font-bold mb-8">Team</h2>
      <p class="text-2xl md:text-3xl font-medium leading-tight max-w-xs">
        Built by founders who understand the cost of doing it all alone.
      </p>
    </div>

    <!-- Right Column -->
    <div class="w-full md:w-3/4">
      <div class="mb-12">
        <p class="text-lg font-medium text-gray-700 leading-relaxed max-w-2xl">
          Delphi AI was born from firsthand experience with the isolation and time constraints of solo entrepreneurship. We're building the mentorship platform we wish we had.
        </p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-x-8 gap-y-12">
        {#each team as member}
          <div class="group cursor-pointer">
            <div class="aspect-[4/5] bg-gray-200 mb-4 overflow-hidden">
              <img src={member.image} alt={member.name} class="w-full h-full object-cover grayscale group-hover:grayscale-0 transition-all duration-500" />
            </div>
            <h3 class="font-bold text-lg">{member.name}</h3>
            <p class="text-gray-500 text-sm mb-3">{member.role}</p>
            <p class="text-sm leading-relaxed mb-4">{member.bio}</p>
            <div class="flex space-x-3 text-gray-400 text-xs">
               <a href={member.linkedin} class="hover:text-primary-600 transition-colors">LinkedIn</a>
               <a href={member.twitter} class="hover:text-primary-600 transition-colors">Twitter</a>
            </div>
          </div>
        {/each}
      </div>

      <div class="mt-12 p-8 bg-primary-50 border border-primary-200">
        <h3 class="text-lg font-bold mb-3">Join Our Mission</h3>
        <p class="text-sm text-gray-700 mb-4">
          We're growing fast and looking for passionate people who believe in democratizing access to wisdom. If you want to help scale mentorship to millions, let's talk.
        </p>
        <a href="#contact" class="text-primary-700 font-semibold hover:text-primary-800 transition-colors">Get in touch →</a>
      </div>
    </div>
  </div>
</section>
