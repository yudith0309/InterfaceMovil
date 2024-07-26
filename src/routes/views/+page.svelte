<script>
	import newlogo from '$lib/imagesprop/newlogo.png'
	import icons8 from '$lib/imagesprop/icons8.png'
	import icons8_menu from '$lib/imagesprop/icons8_menu.png'
	import smartmockups from '$lib/imagesprop/smartmockups.png'
	import icons8_phone from '$lib/imagesprop/icons8_phone.png'
    import icons8_phone_2 from '$lib/imagesprop/icons8_phone_2.png'
	import icons8_phone_256 from '$lib/imagesprop/icons8_phone_256.png' 
	import icons8_call from '$lib/imagesprop/icons8_call.png'
	import line  from '$lib/imagesprop/line6.png'
	import {Button} from 'flowbite-svelte'
	import { Input, Label, Helper } from 'flowbite-svelte'
</script>

  <div class="w-full h-32 p-5 bg-white rounded-bl-3xl rounded-br-3xl justify-between items-end inline-flex">
	<img alt="The project logo" src={newlogo} />
	<div class="h-24 justify-end items-center flex">
	  <div class="text-center text-sky-950 text-xl font-semibold font-variant-numeric:lining-nums leading-6 tracking-wide">1.000.000.000</div>
	  <div class="justify-start items-center gap-2.5 flex">		
		<img class="w-8 h-8" src={icons8}/>
		<div class="w-8 h-8 relative">
		  <img class="w-8 h-8 left-0" src={icons8_menu}/>
		</div>
	  </div>
	</div>
  </div>

  <div class="w-1/6 h-64 relative">
	<div class="w-1/3 h-32 space-x-4">
	  <div class="w-48 h-0 top-[207px] absolute origin-top-left -rotate-90 border-4 border-sky-950"></div>
	  <div class="w-1/3 h-32 relative text-sky-950 text-4xl font-semibold leading-tight">Connecting Businesses, Innovating Communications</div>
	  <div class="w-96 top-20 relative text-stone-950/opacity-60 text-base font-normal leading-tight">Provides a brief overview of the company's specialization in providing VoIP services to small and medium-sized businesses.</div>
	</div>
  </div>
  <img class="object-contain max-w-80 h-64" src={smartmockups} />  


  <div class="h-96 flex-col justify-between items-center gap-2.5 inline-flex">
  <div class="w-96 h-96 py-5 bg-white rounded-3xl flex-col justify-center items-center gap-4 inline-flex">
	<div class="w-5/6 h-20 relative">
	  <div class="w-80 h-20 left-0 top-0 relative text-center text-sky-950 text-3xl font-semibold leading-7">Everything you can do with Towitlinks</div>
	  <img class="w-32 h-1.5 left-20 top-0 relative" src={line} />
	</div> 	
	<div class="w-96 h-80 relative">
	  <img class="w-10 h-10 left-40 top-5 relative" src={icons8_phone} />
	  <div class="w-96 h-80 left-0 top-[80px] absolute flex-col justify-start items-center inline-flex">
		<div class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7">VoIP Calls</div>
		<div class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-xl font-normal leading-7">Make and receive calls from anywhere, anytime, with crystal-clear quality and cost-effective pricing.</div>
	  </div>
	</div>
  </div>

  <div class="w-96 h-80 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-4 inline-flex">
	<img class="w-10 h-10 left-0 top-0 relative" src={icons8_phone_2} />
	<div class="w-96 h-40 left-0 flex-col justify-start items-center flex inline-flex">
	  <div class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7">Text & Fax</div>
	  <div class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-xl font-normal leading-7">Stay connected with colleagues, partners, and clients through integrated text and fax services, eliminating the need for separate devices.</div>
	</div>
  </div>


  <div class="w-96 h-80 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-4 inline-flex">
	<img class="w-10 h-10 left-0 top-0 relative" src={icons8_phone_256} />
	<div class="w-96 h-40 left-0 flex-col justify-start items-center flex">
	  <div class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7">Task Manager</div>
	  <div class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-xl font-normal leading-7">Organize your workload, track progress, and collaborate effectively with our intuitive task manager.</div>
	</div>
  </div>  


  <div class="w-96 h-80 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-4 inline-flex">
	<img class="w-10 h-10 left-0 top-0 relative" src={icons8_call} />
	<div class="w-96 h-44 left-0 flex-col justify-start items-center flex">		
	  <div class= "self-stretch text-center text-sky-950 text-2xl font-semibold leading-7 ">Video Call</div>
	  <div class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-xl font-normal leading-7">Host clear, engaging video conferences with screen sharing, fostering stronger relationships and enhancing communication.</div>	
	</div>
   </div>
  </div>

<style lang="postcss">
	:global(html) {
	  background-color: theme(colors.gray.100);
	}	
</style>