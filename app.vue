<template>
  <div class="min-h-screen bg-white text-gray-900">
    <!-- Navigation -->
    <nav
      class="fixed top-0 w-full bg-white/95 backdrop-blur border-b border-gray-200 z-50"
    >
      <div
        class="max-w-5xl mx-auto px-6 py-4 flex justify-between items-center"
      >
        <h1 class="text-xl font-bold">heythevoz</h1>
        <a href="#contact" class="text-sm font-medium hover:text-blue-600"
          >Book Call</a
        >
      </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-6 max-w-5xl mx-auto">
      <div class="space-y-6">
        <h2 class="text-5xl font-bold leading-tight">
          Digital Marketing Without the Agency Price Tag
        </h2>
        <p class="text-xl text-gray-600 max-w-2xl">
          SEO, campaigns, product launches, and PR—handled by a Swiss digital
          marketing specialist who gets results. No retainers. No long
          contracts.
        </p>
        <button
          @click="scrollToForm"
          class="inline-block px-8 py-3 bg-blue-600 text-white font-medium rounded-lg hover:bg-blue-700 transition"
        >
          Book a Free Strategy Call
        </button>
      </div>
    </section>

    <!-- Social Proof -->
    <section class="bg-gray-50 py-16 px-6">
      <div class="max-w-5xl mx-auto text-center space-y-8">
        <p class="text-gray-600">
          Trusted by SMEs, startups, and marketing agencies across Switzerland.
        </p>
        <div class="space-y-4">
          <p class="text-2xl font-bold">142% Avg ROI on Paid Campaigns</p>
          <p class="text-gray-600">200+ Projects | 18-Month Avg Retention</p>
        </div>
      </div>
    </section>

    <!-- Benefits Grid -->
    <section class="py-20 px-6 max-w-5xl mx-auto">
      <h3 class="text-3xl font-bold mb-12">What You Get</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <!-- Speed -->
        <div class="space-y-4">
          <div class="text-4xl">⚡</div>
          <h4 class="text-xl font-bold">Results in Weeks, Not Months</h4>
          <p class="text-gray-600">
            Most agencies move slow. I don't. First campaign runs in 7 days.
            First results in 30 days.
          </p>
        </div>

        <!-- Flexibility -->
        <div class="space-y-4">
          <div class="text-4xl">🔧</div>
          <h4 class="text-xl font-bold">Hire Exactly What You Need</h4>
          <p class="text-gray-600">
            No retainers. No minimums. Need help with one campaign? Done. Need
            ongoing support? Let's talk.
          </p>
        </div>

        <!-- Full Spectrum -->
        <div class="space-y-4">
          <div class="text-4xl">📦</div>
          <h4 class="text-xl font-bold">
            Everything from SEO to Product Launches
          </h4>
          <p class="text-gray-600">
            SEO • SEM • Campaigns • Launches • PR • Implementation — pick what
            you need or go all-in.
          </p>
        </div>
      </div>
    </section>

    <!-- How It Works -->
    <section class="bg-gray-50 py-20 px-6">
      <div class="max-w-5xl mx-auto">
        <h3 class="text-3xl font-bold mb-12">How We Work Together</h3>
        <div class="grid md:grid-cols-3 gap-8">
          <div>
            <div class="text-3xl font-bold text-blue-600 mb-4">1</div>
            <h4 class="font-bold mb-2">Discovery Call (30 min)</h4>
            <p class="text-gray-600">
              We talk through your goals, challenges, and what success looks
              like. No sales pitch—just a real conversation.
            </p>
          </div>
          <div>
            <div class="text-3xl font-bold text-blue-600 mb-4">2</div>
            <h4 class="font-bold mb-2">Custom Plan</h4>
            <p class="text-gray-600">
              I'll send you a specific plan with strategy, timeline, and cost.
              You decide if it's a fit.
            </p>
          </div>
          <div>
            <div class="text-3xl font-bold text-blue-600 mb-4">3</div>
            <h4 class="font-bold mb-2">Execute & Scale</h4>
            <p class="text-gray-600">
              I handle the work. You track the results. As soon as something
              works, we double down.
            </p>
          </div>
        </div>
      </div>
    </section>

    <!-- FAQ / Objection Handling -->
    <section class="py-20 px-6 max-w-5xl mx-auto">
      <h3 class="text-3xl font-bold mb-12">Common Questions</h3>
      <div class="space-y-8">
        <div>
          <h4 class="font-bold mb-2">How much does this cost?</h4>
          <p class="text-gray-600">
            Depends on scope. A single campaign might be CHF 500-1500. A full
            rebrand with PR might be CHF 5k+. Discovery call is free—we figure
            out what makes sense for you.
          </p>
        </div>
        <div>
          <h4 class="font-bold mb-2">How long until I see results?</h4>
          <p class="text-gray-600">
            First data in 2 weeks (paid ads). Meaningful traction in 30-60 days.
            SEO takes longer—6-12 months to full impact.
          </p>
        </div>
        <div>
          <h4 class="font-bold mb-2">What if I need ongoing support?</h4>
          <p class="text-gray-600">
            Happy to do monthly retainers or project-by-project. Your call.
          </p>
        </div>
        <div>
          <h4 class="font-bold mb-2">Do you work with my industry?</h4>
          <p class="text-gray-600">
            Yep. I've worked with SaaS, e-commerce, agencies, nonprofits, B2B
            services, you name it. Experience across verticals is a feature, not
            a bug.
          </p>
        </div>
      </div>
    </section>

    <!-- CTA Section -->
    <section id="contact" class="bg-blue-600 text-white py-20 px-6">
      <div class="max-w-2xl mx-auto text-center space-y-6">
        <h3 class="text-3xl font-bold">Ready to Grow?</h3>
        <p class="text-lg">
          Book a free strategy call. No obligation. Let's figure out what's
          possible for your business.
        </p>
        <iframe
          src="https://calendly.com/ythevoz/first-contact"
          width="100%"
          height="600"
          frameborder="0"
          class="rounded-lg"
        ></iframe>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-gray-400 py-8 px-6">
      <div class="max-w-5xl mx-auto text-center text-sm">
        <p>© 2026 heythevoz. All rights reserved.</p>
      </div>
    </footer>
  </div>
</template>

<script setup>
const scrollToForm = () => {
  document.getElementById("contact")?.scrollIntoView({ behavior: "smooth" });
};

onMounted(() => {
  // Calendly embed loads via iframe
});
</script>

<style scoped>
button {
  transition: all 0.3s ease;
}

button:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 12px rgba(59, 130, 246, 0.4);
}
</style>
