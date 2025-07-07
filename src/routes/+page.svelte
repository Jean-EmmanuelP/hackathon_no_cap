<script>
    // Placeholder Stripe test link
    const stripeCheckoutUrl = "https://buy.stripe.com/test_4gwcNw2Qw0gQe3KcMM";
  </script>
  
  <div class="bg-black text-gray-200 font-sans antialiased">
    <main class="flex flex-col items-center">
  
      <!-- =========== HERO SECTION =========== -->
      <!-- Centré sur l'aspiration, le résultat final -->
      <section class="w-full min-h-screen flex flex-col justify-center items-center text-center p-4 bg-grid-pattern">
        <div class="max-w-3xl">
          <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tighter leading-tight">
            L'Équipe des Pros.
            <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-400 to-teal-300">Dans Votre Poche.</span>
          </h1>
          <p class="mt-6 max-w-xl mx-auto text-lg md:text-xl text-gray-400">
            GAIPHA réunit nutritionniste, coach sportif et préparateur mental en une seule IA. Pour que vous deveniez la meilleure version de vous-même.
          </p>
          <div class="mt-12">
            <a 
              href={stripeCheckoutUrl} 
              target="_blank" 
              rel="noopener" 
              class="inline-block bg-gradient-to-r from-blue-500 to-teal-400 text-white font-bold py-4 px-10 rounded-full text-lg shadow-lg shadow-blue-500/20 transform hover:scale-105 transition-all duration-300 focus:outline-none focus:ring-4 focus:ring-blue-500/50"
            >
              Devenir mon propre Pro
            </a>
            <p class="mt-4 text-sm text-gray-500">Accès Premium pour 4.99$/mois. Sans engagement.</p>
          </div>
        </div>
      </section>
  
      <!-- =========== ASPIRATION SECTION =========== -->
      <!-- Montre les exemples, crée le lien émotionnel -->
      <section class="w-full max-w-6xl p-4 md:p-8 mt-12">
        <div class="text-center mb-12">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Leur secret ? Une équipe dédiée.</h2>
          <p class="mt-3 text-lg text-gray-400">Votre avantage ? GAIPHA.</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
          <!-- Card 1: Ronaldo -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://assets-fr.imgfoot.com/cristiano-ronaldo-2425-67ab313d2729e.jpg');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Cristiano Ronaldo</h3>
              <p class="mt-1 text-gray-300">Coachs, Nutritionnistes, Analystes.</p>
            </div>
          </div>
          <!-- Card 2: Serena -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://upload.wikimedia.org/wikipedia/commons/5/54/Williams_S._RG18_%2817%29_%2841168711240%29.jpg');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Serena Williams</h3>
              <p class="mt-1 text-gray-300">Entraîneurs, Physiothérapeutes, Stratèges.</p>
            </div>
          </div>
          <!-- Card 3: Musk -->
          <div class="relative h-96 rounded-xl overflow-hidden group">
            <div class="absolute inset-0 bg-cover bg-center transition-transform duration-500 group-hover:scale-110" style="background-image: url('https://fortune.com/img-assets/wp-content/uploads/2024/08/GettyImages-2168697518-e1725048300453.jpg?w=1440&q=90');"></div>
            <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/40 to-transparent"></div>
            <div class="relative z-10 flex flex-col justify-end h-full p-6 text-white">
              <h3 class="text-2xl font-bold">Elon Musk</h3>
              <p class="mt-1 text-gray-300">Conseillers, Analystes, Assistants.</p>
            </div>
          </div>
        </div>
      </section>
  
      <!-- =========== "HOW IT WORKS" / YOUR TEAM SECTION =========== -->
      <!-- Explique concrètement comment GAIPHA est "l'équipe" -->
      <section class="w-full max-w-5xl p-4 md:p-8 mt-20">
        <div class="text-center mb-12">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Voici votre nouvelle équipe</h2>
          <p class="mt-3 text-lg text-gray-400">Trois experts IA dédiés à votre succès, 24/7.</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Expert 1: Nutritionniste -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-green-400">Votre Nutritionniste IA</h3>
            <p class="mt-2 text-gray-400">Crée des plans repas adaptés à vos objectifs, vos goûts et aux produits locaux disponibles.</p>
          </div>
          <!-- Expert 2: Coach Sportif -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-blue-400">Votre Coach Sportif IA</h3>
            <p class="mt-2 text-gray-400">Conçoit des entraînements sur-mesure et suit vos progrès (pas, cardio) juste avec votre téléphone.</p>
          </div>
          <!-- Expert 3: Préparateur Mental -->
          <div class="bg-gray-900 p-6 rounded-lg border border-gray-800 text-center">
            <h3 class="text-xl font-bold text-gray-300">Votre Préparateur Mental IA</h3>
            <p class="mt-2 text-gray-400">Vous garde motivé avec des défis mondiaux, le suivi d'humeur et le soutien de la communauté.</p>
          </div>
        </div>
      </section>
  
      <!-- =========== SOCIAL PROOF & FINAL CTA =========== -->
      <section class="w-full max-w-3xl p-4 md:p-8 mt-20 text-center">
        <figure>
          <blockquote class="italic text-xl text-gray-300">
            “GAIPHA est l'arme secrète de ma préparation. C'est comme avoir un pro qui analyse chaque repas et chaque séance.”
          </blockquote>
          <figcaption class="mt-4 font-semibold text-blue-400">
            – Houman Kelasi, <span class="text-gray-500 font-normal">Athlète et Early User</span>
          </figcaption>
        </figure>
  
        <div class="mt-16">
          <h2 class="text-3xl md:text-4xl font-bold tracking-tight">Prêt à assembler votre équipe ?</h2>
          <p class="mt-3 text-lg text-gray-400">Rejoignez des milliers d'utilisateurs en Inde, au Nigéria et au Brésil qui redéfinissent leurs limites.</p>
          <a 
            href={stripeCheckoutUrl} 
            target="_blank" 
            rel="noopener" 
            class="mt-8 inline-block bg-gradient-to-r from-blue-500 to-teal-400 text-white font-bold py-4 px-10 rounded-full text-lg shadow-lg shadow-blue-500/20 transform hover:scale-105 transition-all duration-300 focus:outline-none focus:ring-4 focus:ring-blue-500/50"
          >
            Obtenir mon accès Premium
          </a>
        </div>
      </section>
  
    </main>
  
    <!-- =========== FOOTER =========== -->
    <footer class="w-full text-center py-10 mt-20 border-t border-gray-800">
      <div class="text-xs text-gray-600 flex flex-col sm:flex-row justify-center items-center gap-2 sm:gap-4">
        <span>© 2024 GAIPHA</span>
        <a href="#" class="hover:text-gray-400 transition">Politique de Confidentialité</a>
        <a href="#" class="hover:text-gray-400 transition">Contact</a>
        <div class="flex items-center gap-1.5">
          <span>Paiements sécurisés par</span>
          <img src="https://www.vectorlogo.zone/logos/stripe/stripe-ar21.svg" alt="Stripe logo" class="h-3 opacity-70" />
        </div>
      </div>
    </footer>
  
  </div>
  
  <!-- CSS pour le fond en grille subtil -->
  <style>
    .bg-grid-pattern {
      background-color: #000000;
      background-image: 
        linear-gradient(rgba(255, 255, 255, 0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255, 255, 255, 0.03) 1px, transparent 1px);
      background-size: 3rem 3rem;
    }
  </style>