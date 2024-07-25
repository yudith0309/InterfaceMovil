<script>
	import newlogo from '$lib/imagesprop/newlogo.png'
	import icons8 from '$lib/imagesprop/icons8.png'
	import icons8_menu from '$lib/imagesprop/icons8_menu.png'
	import smartmockups from '$lib/imagesprop/smartmockups.png'
	import icons8_phone from '$lib/imagesprop/icons8_phone.png'
    import icons8_phone_2 from '$lib/imagesprop/icons8_phone_2.png'
	import icons8_phone_256 from '$lib/imagesprop/icons8_phone_256.png' 
	import icons8_call from '$lib/imagesprop/icons8_call.png'
	import {Button} from 'flowbite-svelte'
	import { Input, Label, Helper } from 'flowbite-svelte'
</script>

  <div class="w-2/5 h-32 p-5 bg-white rounded-bl-3xl rounded-br-3xl justify-between items-end inline-flex">
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

  <div class="w-1/3 h-64 relative">
	<div class="w-1/3 h-32 space-x-4">
	  <div class="w-48 h-0 top-[207px] absolute origin-top-left -rotate-90 border-4 border-sky-950"></div>
	  <div class="w-1/3 h-32 absolute text-sky-950 text-5xl font-semibold leading-tight">Connecting Businesses, Innovating Communications</div>
	  <div class="w-[350px] top-[237px] absolute text-stone-950/opacity-60 text-base font-normal leading-tight">Provides a brief overview of the company's specialization in providing VoIP services to small and medium-sized businesses.</div>
	</div>
  </div>
  <img class="w-96 h-[297px] relative" src={smartmockups} />   


  <div class="w-[390px] h-[412px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[60px] inline-flex">
	<div class="w-[348px] h-[101px] relative">
	  <div class="w-[348px] h-[100px] left-0 top-0 absolute text-center text-sky-950 text-4xl font-semibold font-['Mada'] leading-10">Everything you can do with Towitlinks</div>
	</div>
	<div class="w-[350px] h-[211px] relative">
	  <img class="w-[50px] h-[50px] left-[150px] top-0 absolute" src={icons8_phone} />
	  <div class="w-[350px] h-[131px] left-0 top-[80px] absolute flex-col justify-start items-center inline-flex">
		<div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">VoIP Calls</div>
		<div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Make and receive calls from anywhere, anytime, with crystal-clear quality and cost-effective pricing.</div>
	  </div>
	</div>
  </div>


  <div class="w-[390px] h-[292px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[60px] h-[60px]" src={icons8_phone_2} />
	<div class="w-[350px] h-[131px] left-0 flex-col justify-start items-center flex inline-flex">
	  <div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">Text & Fax</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Stay connected with colleagues, partners, and clients through integrated text and fax services, eliminating the need for separate devices.</div>
	</div>
  </div>


  <div class="w-[390px] h-[251px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[50px] h-[50px]" src={icons8_phone_256} />
	<div class="w-[350px] h-[131px] left-0 flex-col justify-start items-center flex">
	  <div class="self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px]">Task Manager</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Organize your workload, track progress, and collaborate effectively with our intuitive task manager.</div>
	</div>
  </div>  


  <div class="w-[390px] h-[292px] px-[125px] py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[30px] inline-flex">
	<img class="w-[60px] h-[60px]" src={icons8_call} />
	<div class="w-[350px] h-[162px] left-0 flex-col justify-start items-center flex">		
	  <div class= "self-stretch text-center text-sky-950 text-[26px] font-semibold font-['Khula'] leading-[38px] ">Video Call</div>
	  <div class="self-stretch text-center text-sky-950/opacity-60 text-xl font-normal font-['Khula'] leading-[31px]">Host clear, engaging video conferences with screen sharing, fostering stronger relationships and enhancing communication.</div>	
	</div>
   </div> 

	<div class="w-80 h-96 p-5 bg-white rounded-3xl shadow flex-col justify-center items-center gap-6 inline-flex">
		<div class="text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-loose">GET YOUR FREE QUOTE NOW</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-start items-center gap-2.5 inline-flex">
			<div class="w-24 h-6 text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-loose">
				<Label for="first_name" class="mb-2">First name</Label>
			</div>
		</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-start items-center gap-2.5 inline-flex">
		  <div class="w-24 h-6 text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-loose">
			<Label for="first_name" class="mb-2">Last Name</Label></div>
		</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-between items-center inline-flex">
		  <div class="w-16 h-6 relative">
			<div class="w-8 h-4 left-0 top-[8px] absolute text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-loose">+1</div>
			<img class="w-8 h-6 left-[36px] top-0 absolute" src="https://via.placeholder.com/31x24" />
		  </div>
		  <div class="w-36 h-6 text-center text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-loose">
			<Label for="first_name" class="mb-2">Phone Number</Label></div>
		</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-between items-center inline-flex">
		  <div class="w-32 h-12"><span style="text-sky-950/opacity-60 text-sm font-normal font-['Khula'] leading-tight">Country/Region</span><span style="text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-tight">    </span><span style="text-sky-950 text-base font-normal font-['Khula'] leading-tight">Select</span></div>
		  <img class="w-8 h-6" src="https://via.placeholder.com/31x24" />
		</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-between items-center inline-flex">
		  <div class="w-24 h-12"><span style="text-sky-950/opacity-60 text-sm font-normal font-['Khula'] leading-snug">Industry</span><span style="text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-tight">    </span><span style="text-sky-950 text-base font-normal font-['Khula'] leading-tight">Select</span></div>
		  <img class="w-8 h-6" src="https://via.placeholder.com/31x24" />
		</div>
		<div class="self-stretch h-12 px-5 py-2.5 bg-white rounded-2xl border border-sky-950 justify-between items-center inline-flex">
		  <div class="w-24 h-12"><span style="text-sky-950/opacity-60 text-sm font-normal font-['Khula'] leading-tight">Employers</span><span style="text-sky-950/opacity-60 text-base font-normal font-['Khula'] leading-tight">    </span><span style="text-sky-950 text-base font-normal font-['Khula'] leading-tight">Select</span></div>
		  <img class="w-8 h-6" src="https://via.placeholder.com/31x24" />
		</div>
		<div class="h-36 flex-col justify-start items-center gap-2.5 flex">
		  <div class="self-stretch h-20 p-4 bg-neutral-50 rounded justify-start items-start gap-2 inline-flex">
			<div class="w-6 h-6 relative"></div>
			<div class="grow shrink basis-0 text-sky-950 text-base font-normal font-['Khula'] leading-tight">This is a form element that is very long and will become taller the more text that is in it. </div>
		  </div>
			<Button class="w-56 h-14 px-14 py-3.5 bg-orange-400 rounded-2xl shadow justify-center items-center gap-2.5 inline-flex" href="/">Get started</Button>
		</div>
	  </div>


<style lang="postcss">
	:global(html) {
	  background-color: theme(colors.gray.100);
	}	
</style>