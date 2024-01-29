<svelte:head>
	<title>syv.ai - GenAI løsninger</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<style>
    .carousel-item img {
        width: 250px;  /* or any size you want */
        height: 250px; /* or any size you want */
        object-fit: cover; /* this will make sure your images cover the whole space without distorting the aspect ratio */
    }
</style>

<div class="container mx-auto p-4 grid md:grid-cols-4 gap-4">
  <div class="md:col-span-2 flex items-center justify-center flex-col">
    <div class="p-6 text-lg">
      <h1 class="text-center text-3xl font-bold">
		GenAI løsninger der er til at forstå.
	  </h1>
      <p class="text-center text-xl mt-4">
        Vores GenAI løsninger kan hjælpe med at automatisere processer, forbedre beslutningstagning og frigøre dig fra rutinearbejde.
      </p>
	  <div class="flex justify-center mt-4">
	  <button class="btn btn-outline btn-accent btn-lg">Hør mere</button>
    </div>
  </div>
  </div>
  <div class="md:col-span-2">
    <div class="p-6">
		<div class="chat chat-start">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="https://i.imgur.com/IAM61Xf.jpeg" />
			  </div>
			</div>
			<div class="chat-header">
			  Mads
			</div>
			<div class="chat-bubble">Hvad kan syv.ai hjælpe med?</div>
		  </div>
		  <div class="chat chat-end">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="https://i.imgur.com/9fWOV8H.png" />
			  </div>
			</div>
			<div class="chat-header">
			  DanskGPT
			</div>
			<div class="chat-bubble">Syv.ai kan hjælpe med en bred vifte af GenAI løsninger. <br><br> Her er en kort oversigt: <br> - Rådgivning<br> - Foredrag <br> - Undervisning <br> - Udvilking af LLM løsninger <br> - Udvikling af proof of concept </div>
		  </div>
		  <div class="chat chat-start">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="https://i.imgur.com/IAM61Xf.jpeg" />
			  </div>
			</div>
			<div class="chat-header">
			  Mads
			</div>
			<div class="chat-bubble">Hvilke former af undervisning?</div>
		  </div>
		  <div class="chat chat-end">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="https://i.imgur.com/9fWOV8H.png" />
			  </div>
			</div>
			<div class="chat-header">
			  DanskGPT
			</div>
			<div class="chat-bubble">Vi tilbyder bl.a. kurser i ChatGPT/DanskGPT, prompting og AI agenter. Alle kurser bliver skræddersyet til jeres organisation og vi sørger for at niveauet passer til kuristerne.</div>
		  </div>
    </div>
  </div>
</div>

<div class="container mx-auto p-4 grid md:grid-cols-3 gap-4">
	<div class="md:col-span-1 flex items-center justify-center flex-col">
	  <div class="p-6 text-lg">
		<h2 class="text-center text-2xl font-bold">
			Rådgivning om AI
		</h2>
		<p class="text-center text-xl mt-4">
			Hver organisation har unikke udfordringer, hvor mange af dem kan løses med sprogmodeller.
		</p>
	  </div>
	</div>
	<div class="md:col-span-1 flex items-center justify-center flex-col">
	  <div class="p-6 text-lg">
		<h2 class="text-center text-2xl font-bold">
		  Bedste LLM på Dansk
		</h2>
		<p class="text-center text-xl mt-4">
		  Vi har udviklet DanskGPT som er en sprogmodel der på kritiske parametre udkonkurrere ChatGPT.
		</p>
	  </div>
	</div>
	<div class="md:col-span-1 flex items-center justify-center flex-col">
	  <div class="p-6 text-lg">
		<h2 class="text-center text-2xl font-bold">
		  Viden først
		</h2>
		<p class="text-center text-xl mt-4">
		  Vi har lært, at brug af ny teknologi kræver ny viden. Derfor tilbyder vi foredrag og kurser indenfor GenAI.
		</p>
	  </div>
	</div>
</div>


<div class="container mx-auto p-4 grid md:grid-cols-2 gap-4">
  <div class="p-4">
    <h1 class="text-2xl font-bold mb-4">DanskGPT i medierne</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
  </div>
  <div class="carousel carousel-center max-w-md p-4 space-x-4 bg-neutral rounded-box">
	<div class="carousel-item">
		<a href="https://www.dr.dk/lyd/p1/kulturen/kulturen-20231/kulturen-kunst-i-lader-og-debat-om-kultur-i-medierne-11032317473">
			<img src="data:image/png;base64,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" class="rounded-box" />
		</a>
	</div> 
	<div class="carousel-item">
		<a href="https://www.altinget.dk/digital/artikel/ai-raadgiver-hvis-ikke-vi-udvikler-danske-ai-modeller-risikerer-dansk-at-blive-yderligere-marginaliseret">
			<img src="https://www.altinget.dk/A_Logomark.svg" class="rounded-box" />
		</a>
	</div>
	<div class="carousel-item">
		<a href="https://prosabladet.dk/nyheder/nyhed/mads-har-brugt-900-timer-paa-at-udvikle-danskgpt-det-er-gaaet-ret-meget-amok">
			<img src="https://www.prosa.dk/fileadmin/_processed_/7/8/csm_red-logo-m-payoff-rettet-p-r-150_9a52fe8c90.png" class="rounded-box" />
		</a>
	</div>
	<div class="carousel-item">
		<a href="https://prosabladet.dk/nyheder/nyhed/mads-har-brugt-900-timer-paa-at-udvikle-danskgpt-det-er-gaaet-ret-meget-amok">
			<img src="https://i.scdn.co/image/ab6765630000ba8a02c7387af82a6eb644f41cb2" class="rounded-box" />
		</a>
	</div>
  </div>
</div>


<section class="text-gray-600 body-font mt-10 pt-10 pb-10" style="background: linear-gradient(to top, rgba(255, 255, 255, 0), rgba(250, 247, 245, 1)), linear-gradient(to top, #7dc1c6, #e4b152);">
	<h2 class="text-center text-3xl font-bold text-black">
		DanskGPT stats
	</h2>
    <div class="container px-5 py-6 mx-auto">
      <div class="flex flex-wrap -m-4 text-center justify-center items-center">
        <div class="p-4 sm:w-1/4 w-1/2">
          <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">45k</h2>
          <p class="leading-relaxed">Oprettede samtaler</p>
        </div>
        <div class="p-4 sm:w-1/4 w-1/2">
          <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">250k</h2>
          <p class="leading-relaxed">API kald</p>
        </div>
      </div>
    </div>
</section>


