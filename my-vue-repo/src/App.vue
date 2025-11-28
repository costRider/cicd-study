<template>
  <div class="flex flex-col items-center justify-center h-screen bg-black text-white">
    <div class="flex gap-10 mb-10">
      <img 
        src="/assets/cyber-logo.svg" 
        class="h-28 animate-pulse drop-shadow-[0_0_15px_#00faff]" 
        alt="Cyber Logo"
      />
      <img 
        src="/assets/tech-logo.svg" 
        class="h-28 drop-shadow-[0_0_15px_#8b5cf6] animate-glow" 
        alt="Tech Logo"
      />
    </div>

    <h1 class="text-5xl font-extrabold tracking-tight mb-4 neon-title">
      Deploy. Scale. Dominate.
    </h1>

    <p class="text-gray-400 text-lg mb-8">
      Powered by AWS · CodeDeploy · Vue · Vite · Jenkins CI/CD
    </p>

    <HelloWorld msg="Next-Gen Web Deployment" />
  </div>
</template>

<style>
@keyframes glow {
  0% { filter: drop-shadow(0 0 4px #8b5cf6); }
  50% { filter: drop-shadow(0 0 18px #8b5cf6); }
  100% { filter: drop-shadow(0 0 4px #8b5cf6); }
}

.animate-glow {
  animation: glow 2.5s infinite ease-in-out;
}

.neon-title {
  color: #00eaff;
  text-shadow: 0 0 6px #00eaff, 0 0 14px #00eaff, 0 0 26px #00eaff;
}
</style>
