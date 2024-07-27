<script>
  import newlogo from "$lib/imagesprop/newlogo.png";
  import icons8 from "$lib/imagesprop/icons8.png";
  import icons8_menu from "$lib/imagesprop/icons8_menu.png";
  import smartmockups from "$lib/imagesprop/smartmockups.png";
  import icons8_phone from "$lib/imagesprop/icons8_phone.png";
  import icons8_phone_2 from "$lib/imagesprop/icons8_phone_2.png";
  import icons8_phone_256 from "$lib/imagesprop/icons8_phone_256.png";
  import icons8_call from "$lib/imagesprop/icons8_call.png";
  import line from "$lib/imagesprop/line6.png";
  import { Button } from "flowbite-svelte";
  import { Input, Label, Helper } from "flowbite-svelte";
</script>

<div class="ms-3 me-3 flex-col justify-start items-center gap-2.5 inline-flex">
  <div class="w-80 flex-col justify-start items-center gap-10 flex">
    <div
      class="w-full h-32 p-5 bg-white rounded-bl-3xl rounded-br-3xl justify-between items-end inline-flex"
    >
      <img alt="The project logo" src={newlogo} />
      <div class="h-24 justify-end items-center flex">
        <div
          class="text-center text-sky-950 text-xl font-semibold font-variant-numeric:lining-nums leading-6 tracking-wide"
        >
          1.000.000.000
        </div>
        <div class="justify-start items-center gap-2.5 flex">
          <img class="w-8 h-8" src={icons8} />
          <div class="w-8 h-8 relative">
            <img class="w-8 h-8 left-0" src={icons8_menu} />
          </div>
        </div>
      </div>
    </div>

    <div class="w-full h-64 relative inline-flex">
      <div class="w-1/3 h-32 space-x-4">
        <div
          class="w-48 h-0 top-[207px] absolute origin-top-left -rotate-90 border-4 border-sky-950"
        ></div>
        <div
          class="w-1/3 h-32 relative text-sky-950 text-4xl font-semibold leading-tight"
        >
          Connecting Businesses, Innovating Communications
        </div>
        <div
          class="w-80 top-20 relative text-stone-950/opacity-60 text-base font-normal leading-tight"
        >
          Provides a brief overview of the company's specialization in providing
          VoIP services to small and medium-sized businesses.
        </div>
      </div>
    </div>
    <img class="object-contain max-w-80 h-64" src={smartmockups} />

    <div
      class="w-full flex-col justify-between items-center gap-2.5 inline-flex"
    >
      <div
        class="w-full h-96 py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <div class="w-5/6 h-20 relative">
          <div
            class="h-20 left-0 top-0 relative text-center text-sky-950 text-3xl font-semibold leading-7"
          >
            Everything you can do with Towitlinks
          </div>
          <img class="w-32 h-1.5 left-20 top-0 relative" src={line} />
        </div>
        <div class="w-96 h-60 relative">
          <img class="w-10 h-10 left-40 top-5 relative" src={icons8_phone} />
          <div
            class="w-96 h-80 left-0 top-[80px] absolute flex-col justify-start items-center inline-flex"
          >
            <div
              class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7"
            >
              VoIP Calls
            </div>
            <div
              class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-lg font-normal leading-7"
            >
              Make and receive calls from anywhere, anytime, with crystal-clear
              quality and cost-effective pricing.
            </div>
          </div>
        </div>
      </div>

      <div
        class="w-full h-64 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <img class="w-10 h-10 left-0 top-0 relative" src={icons8_phone_2} />
        <div
          class="w-96 h-40 left-0 flex-col justify-start items-center flex inline-flex"
        >
          <div
            class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7"
          >
            Text & Fax
          </div>
          <div
            class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-lg font-normal leading-7"
          >
            Stay connected with colleagues, partners, and clients through
            integrated text and fax services, eliminating the need for separate
            devices.
          </div>
        </div>
      </div>

      <div
        class="w-full h-60 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <img class="w-10 h-10 left-0 top-0 relative" src={icons8_phone_256} />
        <div class="w-96 h-40 left-0 flex-col justify-start items-center flex">
          <div
            class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7"
          >
            Task Manager
          </div>
          <div
            class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-lg font-normal leading-7"
          >
            Organize your workload, track progress, and collaborate effectively
            with our intuitive task manager.
          </div>
        </div>
      </div>

      <div
        class="w-full h-60 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <img class="w-10 h-10 left-0 top-0 relative" src={icons8_call} />
        <div class="w-96 h-44 left-0 flex-col justify-start items-center flex">
          <div
            class="self-stretch text-center text-sky-950 text-2xl font-semibold leading-7"
          >
            Video Call
          </div>
          <div
            class="w-80 h-10 relative text-center text-sky-950/opacity-60 text-lg font-normal leading-7"
          >
            Host clear, engaging video conferences with screen sharing,
            fostering stronger relationships and enhancing communication.
          </div>
        </div>
      </div>
    </div>

    <div
      class="w-[310px] h-[696px] p-5 bg-white rounded-3xl shadow flex-col justify-center items-center gap-[25px] inline-flex"
    >
      <div
        class="text-[#052f47]/60 text-base font-normal font-['Khula'] leading-[31px]"
      >
        GET YOUR FREE QUOTE NOW
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-start items-center gap-2.5 inline-flex"
      >
        <div
          class="w-[95px] h-[23px] text-[#052f47]/60 text-base font-normal font-['Khula'] leading-[31px]"
        >
          First Name
        </div>
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-start items-center gap-2.5 inline-flex"
      >
        <div
          class="w-[95px] h-[23px] text-[#052f47]/60 text-base font-normal font-['Khula'] leading-[31px]"
        >
          Last Name
        </div>
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-between items-center inline-flex"
      >
        <div class="w-[67px] h-6 relative">
          <div
            class="w-[31px] h-4 left-0 top-[8px] absolute text-[#052f47]/60 text-base font-normal font-['Khula'] leading-[31px]"
          >
            +1
          </div>
          <img
            class="w-[31px] h-6 left-[36px] top-0 absolute"
            src="https://via.placeholder.com/31x24"
          />
        </div>
        <div
          class="w-[139px] h-[23px] text-center text-[#052f47]/60 text-base font-normal font-['Khula'] leading-[31px]"
        >
          Phone Number
        </div>
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-between items-center inline-flex"
      >
        <div class="w-[134px] h-[49px]">
          <span
            style="text-[#052f47]/60 text-sm font-normal font-['Khula'] leading-tight"
            >Country/Region</span
          ><span
            style="text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
          >
          </span><span
            style="text-[#052f47] text-base font-normal font-['Khula'] leading-tight"
            >Select</span
          >
        </div>
        <img class="w-[31px] h-6" src="https://via.placeholder.com/31x24" />
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-between items-center inline-flex"
      >
        <div class="w-[90px] h-[49px]">
          <span
            style="text-[#052f47]/60 text-sm font-normal font-['Khula'] leading-snug"
            >Industry</span
          ><span
            style="text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
          >
          </span><span
            style="text-[#052f47] text-base font-normal font-['Khula'] leading-tight"
            >Select</span
          >
        </div>
        <img class="w-[31px] h-6" src="https://via.placeholder.com/31x24" />
      </div>
      <div
        class="self-stretch h-[50px] px-5 py-2.5 bg-white rounded-2xl border border-[#052f47] justify-between items-center inline-flex"
      >
        <div class="w-[90px] h-[49px]">
          <span
            style="text-[#052f47]/60 text-sm font-normal font-['Khula'] leading-tight"
            >Employers</span
          ><span
            style="text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
          >
          </span><span
            style="text-[#052f47] text-base font-normal font-['Khula'] leading-tight"
            >Select</span
          >
        </div>
        <img class="w-[31px] h-6" src="https://via.placeholder.com/31x24" />
      </div>
      <div class="h-[150px] flex-col justify-start items-center gap-2.5 flex">
        <div
          class="self-stretch h-20 p-4 bg-[#fdfcfb] rounded justify-start items-start gap-2 inline-flex"
        >
          <div class="w-6 h-6 relative"></div>
          <div
            class="grow shrink basis-0 text-[#052f47] text-base font-normal font-['Khula'] leading-tight"
          >
            This is a form element that is very long and will become taller the
            more text that is in it.
          </div>
        </div>
        <div
          class="w-[220px] h-[60px] px-[55px] py-3.5 bg-[#f68737] rounded-2xl shadow justify-center items-center gap-2.5 inline-flex"
        >
          <div
            class="w-[87px] h-[25px] text-white text-base font-normal font-['Khula'] leading-[31px] tracking-wide"
          >
            Get started
          </div>
        </div>
      </div>
    </div>

    <div
      class="h-[117px] px-[25px] py-2.5 bg-[#20ccf8] flex-col justify-center items-center gap-5 inline-flex"
    >
      <div
        class="text-center text-[#ebfeff] text-[26px] font-semibold font-['Khula'] leading-[38px] tracking-[2.60px]"
      >
        Trusted By 200k+ Business
      </div>
    </div>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>
