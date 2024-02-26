<svelte:head>
	<title>syv.ai - GenAI løsninger</title>
	<meta name="description" content="Syv.ai er din partner i GenAI verdenen." />
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
		GenAI-løsninger, der er lette at forstå.
	  </h1>
      <p class="text-center text-xl mt-4">
        Vores GenAI-løsninger kan hjælpe med at automatisere processer, forbedre beslutningstagning og frigøre dig fra rutinearbejde.
      </p>
	  <div class="flex justify-center mt-4">
	  <button class="btn btn-outline btn-accent btn-lg"><a href="/kontakt">Hør mere</a></button>
    </div>
  </div>
  </div>
  <div class="md:col-span-2">
    <div class="p-6">
		<div class="chat chat-start">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="/icons8-person-96.png" />
			  </div>
			</div>
			<div class="chat-header">
			  Dig
			</div>
			<div class="chat-bubble">Hvad kan syv.ai hjælpe med?</div>
		  </div>
		  <div class="chat chat-end">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="/tiny-danskgpt.png" />
			  </div>
			</div>
			<div class="chat-header">
			  DanskGPT
			</div>
			<div class="chat-bubble">Syv.ai kan hjælpe med en bred vifte af GenAI-løsninger. <br><br> Her er en kort oversigt: <br> - Private chatbots<br> - Rådgivning<br> - Foredrag <br> - Undervisning <br> - Udvikling af LLM-løsninger <br> - Udvikling af proof of concept </div>
		  </div>
		  <div class="chat chat-start">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="/icons8-person-96.png" />
			  </div>
			</div>
			<div class="chat-header">
			  Dig
			</div>
			<div class="chat-bubble">Hvilke former for undervisning tilbydes?</div>
		  </div>
		  <div class="chat chat-end">
			<div class="chat-image avatar">
			  <div class="w-10 rounded-full">
				<img alt="Tailwind CSS chat bubble component" src="/tiny-danskgpt.png" />
			  </div>
			</div>
			<div class="chat-header">
			  DanskGPT
			</div>
			<div class="chat-bubble">Vi tilbyder blandt andet kurser i ChatGPT/DanskGPT, prompting og AI-agenter. Alle kurser bliver skræddersyet til jeres organisation, og vi sørger for, at niveauet passer til kursisterne.</div>
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
			Hver organisation står over for unikke udfordringer, mange af dem kan løses med sprogmodeller.
		</p>
	  </div>
	</div>
	<div class="md:col-span-1 flex items-center justify-center flex-col">
	  <div class="p-6 text-lg">
		<h2 class="text-center text-2xl font-bold">
		  Bedste LLM på Dansk
		</h2>
		<p class="text-center text-xl mt-4">
		    Vi har udviklet DanskGPT, som er en sprogmodel, der på kritiske parametre overgår ChatGPT.
		</p>
	  </div>
	</div>
	<div class="md:col-span-1 flex items-center justify-center flex-col">
	  <div class="p-6 text-lg">
		<h2 class="text-center text-2xl font-bold">
		  Viden først
		</h2>
		<p class="text-center text-xl mt-4">
			Vi har lært, at brug af ny teknologi kræver ny viden. Derfor tilbyder vi foredrag og kurser inden for GenAI.
		</p>
	  </div>
	</div>
</div>


<div class="container mx-auto p-4 grid md:grid-cols-2 gap-4 mt-10 text-center">
  <div class="p-4">
    <h1 class="text-3xl font-bold p-4">DanskGPT i medierne</h1>
    <p class="text-xl">Historien om DanskGPT har siden lanceringen i august 2023 været omtalt i mange store danske medier, herunder to radiointerviews hos DR, tre podcasts, og skrevne artikler hos Version2, Prosa, IDA og ITWatch.</p>
  </div>
  <div class="carousel carousel-center max-w-md p-4 space-x-4 bg-neutral rounded-box">
	<div class="carousel-item">
		<a href="https://www.dr.dk/lyd/p1/kulturen/kulturen-20231/kulturen-kunst-i-lader-og-debat-om-kultur-i-medierne-11032317473">
			<img src="data:image/png;base64,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" class="rounded-box" />
		</a>
	</div>
	<div class="carousel-item">
		<a href="https://itwatch.dk/ITNyt/Profiler/article16501575.ece">
			<img src="https://media.licdn.com/dms/image/C4E0BAQFiUAeTm1kQVw/company-logo_200_200/0/1671403410537/itwatch_logo?e=2147483647&v=beta&t=VGG_XzLecYZiwnqdl6tgDQ8HQUF6PG2mhjr0Qr1ADxc" class="rounded-box" />
		</a>
	</div>
	<div class="carousel-item">
		<a href="https://www.altinget.dk/digital/artikel/ai-raadgiver-hvis-ikke-vi-udvikler-danske-ai-modeller-risikerer-dansk-at-blive-yderligere-marginaliseret">
			<img src="https://www.altinget.dk/A_Logomark.svg" class="rounded-box" />
		</a>
	</div>
	<div class="carousel-item">
		<a href="https://www.version2.dk/artikel/mads-har-brugt-950-timer-paa-udvikle-dansk-pendant-til-chatgpt">
			<img src="https://www.version2.dk/sites/mi/files/styles/automatic_crop_16_9/public/2017-12/v21280x1024.jpg.webp?itok=9mRgZ5-l" class="rounded-box" />
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

<div class="py-16 pt-32">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                DanskGPT
            </h2>
            <p class="mt-3 text-xl text-gray-500 sm:mt-4">
                Nyd ChatGPT's færdigheder med 100% privatlivssikkerhed
            </p>
        </div>
    </div>
    <div class="mt-10 pb-1">
        <div class="relative">
            <div class="absolute inset-0 h-1/2"></div>
            <div class="relative max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="max-w-4xl mx-auto">
                    <dl class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-3">
                        <div class="flex flex-col border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r">
                            <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                                Oprettede samtaler
                            </dt>
                            <dd class="order-1 text-5xl font-extrabold text-gray-700">+55.000</dd>
                        </div>
                        <div
                            class="flex flex-col border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r">
                            <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                                API-kald
                            </dt>
                            <dd class="order-1 text-5xl font-extrabold text-gray-700">+300.000</dd>
                        </div>
                        <div class="flex flex-col border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l">
                            <dt class="order-2 mt-2 text-lg leading-6 font-medium text-gray-500">
                                Data sendt udenfor Danmark
                            </dt>
                            <dd class="order-1 text-5xl font-extrabold text-gray-700">0</dd>
                        </div>
                    </dl>
                </div>
            </div>
        </div>
    </div>
</div>


