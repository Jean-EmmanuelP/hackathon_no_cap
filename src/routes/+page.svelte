<script>
    // Placeholder Stripe test link
    const stripeCheckoutUrl = "https://buy.stripe.com/test_4gwcNw2Qw0gQe3KcMM";
  </script>
  
  <div class="relative min-h-screen bg-black text-gray-200 font-sans antialiased">
  
    <!-- =========== LANGUAGE SELECTOR =========== -->
    <!-- A subtle flag/globe icon in the top-right corner -->
    <div class="absolute top-4 right-4 sm:top-6 sm:right-6 z-50">
      <button class="flex items-center gap-2 text-sm text-gray-400 hover:text-white transition-colors">
        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
          <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 01-9 9m9-9a9 9 0 00-9-9m9 9H3m9 9a9 9 0 01-9-9m9 9V3m-9 9h18" />
        </svg>
        <span>EN</span>
      </button>
    </div>
  
    <main class="flex flex-col items-center">
  
      <!-- =========== HERO SECTION =========== -->
      <!-- Focused on the ultimate aspirational outcome -->
      <section class="w-full min-h-screen flex flex-col justify-center items-center text-center p-4 bg-grid-pattern">
        <div class="max-w-3xl">
          <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tighter leading-tight">
            A Pro Team's Edge.
            <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-teal-300">In Your Pocket.</span>
          </h1>
          <p class="mt-6 max-w-xl mx-auto text-lg md:text-xl text-gray-400">
            GAIPHA is your all-in-one AI nutritionist, fitness coach, and mental strategist. Built to unlock your peak performance.
          </p>
          <div class="mt-12">
            <a 
              href={stripeCheckoutUrl} 
              target="_blank" 
              rel="noopener" 
              class="inline-block bg-gradient-to-r from-blue-500 to-teal-400 text-white font-bold py-4 px-10 rounded-full text-lg shadow-lg shadow-blue-500/20 transform hover:scale-105 transition-all duration-300 focus:outline-none focus:ring-4 focus:ring-blue-500/50"
            >
              Become My Own Pro
            </a>
            <p class="mt-4 text-sm text-gray-500">Premium access for $4.99/month. Cancel anytime.</p>
          </div>
        </div>
      </section>
  
      <!-- =========== ASPIRATION SECTION =========== -->
      <!-- Visualizing excellence, creating an emotional link -->
      <section class="w-full max-w-6xl p-4 md:p-8 mt-12">
        <div class="text-center mb-12">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Their secret? A dedicated team.</h2>
          <p class="mt-3 text-lg text-gray-400">Your advantage? GAIPHA.</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
          <!-- Card 1: Ronaldo -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://assets-fr.imgfoot.com/cristiano-ronaldo-2425-67ab313d2729e.jpg');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Cristiano Ronaldo</h3>
              <p class="mt-1 text-gray-300">Coaches, Nutritionists, Analysts.</p>
            </div>
          </div>
          <!-- Card 2: Serena -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://upload.wikimedia.org/wikipedia/commons/5/54/Williams_S._RG18_%2817%29_%2841168711240%29.jpg');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Serena Williams</h3>
              <p class="mt-1 text-gray-300">Trainers, Physiotherapists, Strategists.</p>
            </div>
          </div>
          <!-- Card 3: Musk -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://fortune.com/img-assets/wp-content/uploads/2024/08/GettyImages-2168697518-e1725048300453.jpg?w=1440&q=90');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Elon Musk</h3>
              <p class="mt-1 text-gray-300">Advisors, Analysts, Assistants.</p>
            </div>
          </div>
        </div>
      </section>
  
      <!-- =========== "HOW IT WORKS" / YOUR TEAM SECTION =========== -->
      <!-- Explaining how GAIPHA becomes "the team" -->
      <section class="w-full max-w-5xl p-4 md:p-8 mt-20">
        <div class="text-center mb-12">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Meet Your New Team</h2>
          <p class="mt-3 text-lg text-gray-400">Three AI experts dedicated to your success, 24/7.</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Expert 1: Nutritionist -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-green-400">Your AI Nutritionist</h3>
            <p class="mt-2 text-gray-400">Creates meal plans tailored to your goals, tastes, and local foods.</p>
          </div>
          <!-- Expert 2: Fitness Coach -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-blue-400">Your AI Fitness Coach</h3>
            <p class="mt-2 text-gray-400">Designs custom workouts and tracks progress (steps, cardio) with just your phone.</p>
          </div>
          <!-- Expert 3: Mental Strategist -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-gray-300">Your AI Mental Strategist</h3>
            <p class="mt-2 text-gray-400">Keeps you motivated with global challenges, mood tracking, and community support.</p>
          </div>
        </div>
      </section>
  
      <!-- =========== SOCIAL PROOF & FINAL CTA =========== -->
      <section class="w-full max-w-3xl p-4 md:p-8 mt-20 text-center">
        <figure>
          <blockquote class="italic text-xl text-gray-300">
            “GAIPHA is the secret weapon in my prep. It’s like having a pro analyzing every meal and every session.”
          </blockquote>
          <figcaption class="mt-4 font-semibold text-blue-400">
            – Houman Kelasi, <span class="text-gray-500 font-normal">Athlete & Early User</span>
          </figcaption>
        </figure>
  
        <div class="mt-16">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Ready to build your team?</h2>
          <p class="mt-3 text-lg text-gray-400">Join thousands of users in India, Nigeria, and Brazil who are redefining their limits.</p>
          <a 
            href={stripeCheckoutUrl} 
            target="_blank" 
            rel="noopener" 
            class="mt-8 inline-block bg-gradient-to-r from-blue-500 to-teal-400 text-white font-bold py-4 px-10 rounded-full text-lg shadow-lg shadow-blue-500/20 transform hover:scale-105 transition-all duration-300 focus:outline-none focus:ring-4 focus:ring-blue-500/50"
          >
            Get My Premium Access
          </a>
        </div>
      </section>
  
    </main>
  
    <!-- =========== FOOTER =========== -->
    <footer class="w-full text-center py-10 mt-20 border-t border-gray-800">
      <div class="text-xs text-gray-600 flex flex-col sm:flex-row justify-center items-center gap-2 sm:gap-4">
        <span>© 2024 GAIPHA</span>
        <a href="#" class="hover:text-gray-400 transition">Privacy Policy</a>
        <a href="#" class="hover:text-gray-400 transition">Contact</a>
        <div class="flex items-center gap-1.5">
          <span>Secure payments by</span>
          <img src="https://www.vectorlogo.zone/logos/stripe/stripe-ar21.svg" alt="Stripe logo" class="h-3 opacity-70" />
        </div>
      </div>
    </footer>
  
  </div>
  
  <!-- CSS for the subtle grid background pattern -->
  <style>
    .bg-grid-pattern {
      background-color: #000000;
      background-image: 
        linear-gradient(rgba(255, 255, 255, 0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
      background-size: 3rem 3rem;
    }
  </style>