<script>
  import { Button } from "flowbite-svelte";
  import { Input, Label, Helper } from "flowbite-svelte";
</script>

<div class="ms-3 me-3 flex-col justify-start items-center gap-2.5 inline-flex">
  <div class="w-80 flex-col justify-start items-center gap-10 flex">
    <div
      class="w-full h-32 p-5 bg-white rounded-bl-3xl rounded-br-3xl justify-between items-end inline-flex"
    >
      <img alt="The project logo" src="images/newlogo.png" />
      <div class="h-24 justify-end items-center flex">
        <div
          class="text-center text-[#052f47] text-xl font-semibold font-variant-numeric:lining-nums leading-6 tracking-wide"
        >
          1.000.000.000
        </div>
        <div class="justify-start items-center gap-2.5 flex">
          <img class="w-8 h-8" src="images/icons8.png" />
          <div class="w-8 h-8 relative">
            <img class="w-8 h-8 left-0" src="images/icons8_menu.png" />
          </div>
        </div>
      </div>
    </div>

    <div class="w-full h-64 relative inline-flex">
      <div class="w-1/3 h-32 space-x-4">
        <div
          class="w-48 h-0 top-[207px] absolute origin-top-left -rotate-90 border-4 border-[#052f47]"
        ></div>
        <div
          class="w-1/3 h-32 relative text-[#052f47] text-4xl font-semibold leading-tight"
        >
          Connecting Businesses, Innovating Communications
        </div>
        <div
          class="w-80 top-20 relative text-[#111010]/60 text-base font-normal leading-tight"
        >
          Provides a brief overview of the company's specialization in providing
          VoIP services to small and medium-sized businesses.
        </div>
      </div>
    </div>
    <img class="object-contain max-w-80 h-64" src="images/smartmockups.png" />

    <div
      class="w-full flex-col justify-between items-center gap-2.5 inline-flex"
    >
      <div
        class="w-full h-96 py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <div class="w-80 h-24 relative">
          <div
            class="h-20 left-0 top-0 relative text-center text-[#052f47] text-3xl font-semibold leading-7"
          >
            Everything you can do with Towitlinks
          </div>
          <img class="w-32 h-1 left-20 top-0 relative" src="images/line6.png" />
        </div>
        <div class="w-96 h-60 relative">
          <img
            class="w-10 h-10 left-40 top-5 relative"
            src="images/icons8_phone.png"
          />
          <div
            class="w-96 h-80 left-0 top-[80px] absolute flex-col justify-start items-center inline-flex"
          >
            <div
              class="self-stretch text-center text-[#052f47] text-2xl font-semibold leading-7"
            >
              VoIP Calls
            </div>
            <div
              class="w-80 h-10 relative text-center text-[#052f47]/60 text-lg font-normal leading-7"
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
        <img
          class="w-10 h-10 left-0 top-0 relative"
          src="images/icons8_phone_2.png"
        />
        <div
          class="w-96 h-40 left-0 flex-col justify-start items-center flex inline-flex"
        >
          <div
            class="self-stretch text-center text-[#052f47] text-2xl font-semibold leading-7"
          >
            Text & Fax
          </div>
          <div
            class="w-80 h-10 relative text-center text-[#052f47]/60 text-lg font-normal leading-7"
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
        <img
          class="w-10 h-10 left-0 top-0 relative"
          src="images/icons8_phone_256.png"
        />
        <div class="w-96 h-40 left-0 flex-col justify-start items-center flex">
          <div
            class="self-stretch text-center text-[#052f47] text-2xl font-semibold leading-7"
          >
            Task Manager
          </div>
          <div
            class="w-80 h-10 relative text-center text-[#052f47]/60 text-lg font-normal leading-7"
          >
            Organize your workload, track progress, and collaborate effectively
            with our intuitive task manager.
          </div>
        </div>
      </div>

      <div
        class="w-full h-60 relative py-5 bg-white rounded-3xl flex-col justify-center items-center gap-6 inline-flex"
      >
        <img
          class="w-10 h-10 left-0 top-0 relative"
          src="images/icons8_call.png"
        />
        <div class="w-96 h-44 left-0 flex-col justify-start items-center flex">
          <div
            class="self-stretch text-center text-[#052f47] text-2xl font-semibold leading-7"
          >
            Video Call
          </div>
          <div
            class="w-80 h-10 relative text-center text-[#052f47]/60 text-lg font-normal leading-7"
          >
            Host clear, engaging video conferences with screen sharing,
            fostering stronger relationships and enhancing communication.
          </div>
        </div>
      </div>
    </div>

    <div
      class="w-72 h-3/6 p-5 bg-white rounded-3xl shadow flex-col justify-center items-center gap-4 inline-flex"
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
            src="images/icons8_expand.png"
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
        <img class="w-[31px] h-6" src="images/icons8_expand.png" />
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
        <img class="w-[31px] h-6" src="images/icons8_expand.png" />
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
        <img class="w-[31px] h-6" src="images/icons8_expand.png" />
      </div>
      <div class="h-[150px] flex-col justify-start items-center gap-2.5 flex">
        <div
          class="self-stretch h-20 p-4 bg-[#fdfcfb] rounded justify-start items-start gap-2 inline-flex"
        >
          <div class="w-2 h-6 relative"></div>
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
      class="w-full h-[117px] px-[25px] py-2.5 bg-[#20ccf8] flex-col justify-center items-center gap-5 inline-flex"
    >
      <div
        class="text-center text-[#ebfeff] text-[26px] font-semibold font-['Khula'] leading-[38px] tracking-[2.60px]"
      >
        Trusted By 200k+ Business
      </div>
    </div>
  </div>

  <div
    class="w-full h-5/6 bg-white rounded-3xl flex-col justify-start items-center gap-4 inline-flex"
  >
    <div class="h-16 justify-center items-center inline-flex">
      <div
        class="w-[348px] text-center text-[#052f47] text-[40px] font-semibold font-['Mada'] leading-[50px]"
      >
        Why Towitlinks?
      </div>
    </div>
    <div class="self-stretch p-5 justify-start items-start gap-5 inline-flex">
      <div class="justify-start items-start gap-5 flex">
        <img class="w-[60px] h-[60px]" src="images/icons8_p.png" />
        <div class="w-[263px] flex-col justify-start items-center inline-flex">
          <div
            class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
          >
            Unmatched Reliability
          </div>
          <div
            class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
          >
            We prioritize uptime and security, ensuring your communication is
            always accessible and your data is safe.
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch p-5 justify-start items-start gap-5 inline-flex">
      <div class="justify-start items-start gap-5 flex">
        <img class="w-[60px] h-[60px]" src="images/icons8_p2.png" />
        <div class="w-[263px] flex-col justify-start items-center inline-flex">
          <div
            class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
          >
            Seamless Integration
          </div>
          <div
            class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
          >
            Our platform integrates seamlessly with existing systems, minimizing
            disruption and maximizing user-friendliness.
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch p-5 justify-start items-start gap-5 inline-flex">
      <div class="justify-start items-start gap-5 flex">
        <img class="w-[60px] h-[60px]" src="images/icons825.png" />
        <div class="w-[263px] flex-col justify-start items-center inline-flex">
          <div
            class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
          >
            Affordable Pricing
          </div>
          <div
            class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
          >
            We offer competitive pricing plans tailored to your specific needs,
            helping you save on communication costs without sacrificing quality.
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch p-5 justify-start items-start gap-5 inline-flex">
      <div class="justify-start items-start gap-5 flex">
        <img class="w-[60px] h-[60px]" src="images/icons822.png" />
        <div class="w-[263px] flex-col justify-start items-center inline-flex">
          <div
            class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
          >
            Exceptional Support
          </div>
          <div
            class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
          >
            Our dedicated customer support team is available 24/7 to address
            your questions and ensure a smooth experience.
          </div>
        </div>
      </div>
    </div>
    <div class="self-stretch p-5 justify-start items-start gap-5 inline-flex">
      <div class="justify-start items-start gap-5 flex">
        <img class="w-[60px] h-[60px]" src="images/icons8222.png" />
        <div class="w-[263px] flex-col justify-start items-center inline-flex">
          <div
            class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
          >
            Cutting-Edge Technology
          </div>
          <div
            class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
          >
            We constantly invest in the latest technology to provide you with
            the most advanced and efficient communication tools available.
          </div>
        </div>
      </div>
    </div>
  </div>

  <img class="w-[346px] h-[712px] rounded-[50px]" src="images/smart.png" />

  <div
    class="w-full h-5/6 py-5 bg-white rounded-3xl flex-col justify-center items-center gap-[5px] inline-flex"
  >
    <div class="h-[100px] justify-center items-center inline-flex">
      <div
        class="w-[348px] text-center text-[#052f47] text-[40px] font-semibold font-['Mada'] leading-[50px]"
      >
        Easy Setup
      </div>
    </div>
    <div class="w-[310px] flex-col justify-start items-start gap-5 inline-flex">
      <img class="w-[60px] h-[60px]" src="images/icons82562.png" />
    </div>
    <div class="w-[310px] flex-col justify-start items-center inline-flex">
      <div
        class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
      >
        Sign Up
      </div>
      <div
        class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
      >
        Create a free account on our website. It only takes a minute and you'll
        gain access to all the features you need to get started.
      </div>
    </div>
    <div class="text-[#f46d1b] text-xl font-bold font-['Khula'] leading-[31px]">
      1
    </div>
    <div class="w-[310px] flex-col justify-start items-start gap-5 inline-flex">
      <img class="w-[60px] h-[60px]" src="images/icons8_p22.png" />
    </div>
    <div class="w-[310px] flex-col justify-start items-center inline-flex">
      <div
        class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
      >
        Explore & Customize
      </div>
      <div
        class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
      >
        Familiarize yourself with our platform and personalize your settings to
        fit your specific business needs.
      </div>
    </div>
    <div class="text-[#f46d1b] text-xl font-bold font-['Khula'] leading-[31px]">
      2
    </div>
    <div class="w-[310px] flex-col justify-start items-start gap-5 inline-flex">
      <img class="w-[60px] h-[60px]" src="images/icons8_ph22.png" />
    </div>
    <div class="w-[310px] flex-col justify-start items-center inline-flex">
      <div
        class="self-stretch text-[#052f47] text-[26px] font-semibold font-['Khula'] leading-[38px]"
      >
        Connect & Communicate
      </div>
      <div
        class="self-stretch text-[#052f47]/60 text-xl font-normal font-['Khula'] leading-[31px]"
      >
        Start making calls, sending texts and faxes, and managing tasks with
        your team. We're here to support you every step of the way.
      </div>
    </div>
    <div class="text-[#f46d1b] text-xl font-bold font-['Khula'] leading-[31px]">
      3
    </div>
  </div>

  <div
    class="w-full h-5/6 p-2.5 flex-col justify-center items-center gap-2.5 inline-flex"
  >
    <div
      class="w-[367px] h-[168px] text-center text-black text-[45px] font-semibold font-['Mada'] leading-[52px]"
    >
      FAQs about VoIP services
    </div>
    <div class="w-[350px] h-[145px] relative">
      <div
        class="w-[350px] h-[114px] px-5 pt-[30px] pb-5 left-0 top-[31px] absolute bg-[#f4f4f4] rounded-bl-2xl rounded-br-2xl justify-center items-center gap-2.5 inline-flex"
      >
        <div
          class="w-[310px] text-[#052f47]/60 text-sm font-normal font-['Khula'] leading-none"
        >
          This is a fundamental question you should definitely address. Explain
          in simple terms what VoIP is: voice over internet protocol. How it
          uses the internet to make calls, and how it differs from traditional
          phone lines.
        </div>
      </div>
      <div
        class="w-[350px] h-10 px-5 left-0 top-0 relative bg-white rounded-2xl justify-between items-center inline-flex"
      >
        <div
          class="w-[137px] h-[49px] text-[#052f47] text-xl font-normal font-['Khula'] leading-[31px]"
        >
          What is VoIP?
        </div>
        <img
          class="w-[31px] h-6 origin-top-left -rotate-180"
          src="https://via.placeholder.com/31x24"
        />
      </div>
    </div>
    <div class="justify-start items-start inline-flex">
      <div class="h-[55px] justify-start items-start flex">
        <div
          class="w-[350px] h-[55px] px-5 py-2.5 bg-white rounded-2xl justify-between items-center flex"
        >
          <div
            class="text-[#052f47] text-xl font-normal font-['Khula'] leading-[31px]"
          >
            How does VoIP work?
          </div>
          <img class="w-[31px] h-6" src="images/icons8_expand.png" />
        </div>
      </div>
    </div>
    <div class="justify-start items-start inline-flex">
      <div class="h-[55px] justify-start items-start flex">
        <div
          class="w-[350px] h-[55px] px-5 py-2.5 bg-white rounded-2xl justify-between items-center flex"
        >
          <div
            class="text-[#052f47] text-xl font-normal font-['Khula'] leading-[31px]"
          >
            Is VoIP secure?
          </div>
          <img class="w-[31px] h-6" src="images/icons8_expand.png" />
        </div>
      </div>
    </div>
    <div class="justify-start items-start inline-flex">
      <div class="h-[55px] justify-start items-start flex">
        <div
          class="w-[350px] h-[55px] px-5 py-2.5 bg-white rounded-2xl justify-between items-center flex"
        >
          <div
            class="text-[#052f47] text-xl font-normal font-['Khula'] leading-[31px]"
          >
            Who can benefit from using VoIP?
          </div>
          <img class="w-[31px] h-6" src="images/icons8_expand.png" />
        </div>
      </div>
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

  <div
    class="h-[533px] p-5 bg-[#f9f5f5] flex-col justify-center items-center gap-2.5 inline-flex"
  >
    <div class="h-[103px] flex-col justify-start items-center gap-2.5 flex">
      <div class="w-[129px] h-[31px] relative">
        <div class="w-[99px] left-[29px] top-[3px] absolute text-center">
          <span
            style="text-[#052f47] text-xl font-extrabold font-['Inter'] leading-[31px]"
          >
            Towit</span
          ><span
            style="text-[#052f47] text-xl font-normal font-['Khula'] leading-[31px]"
            >links</span
          >
        </div>
      </div>
      <div
        class="w-[348px] text-center text-[#052f47] text-base font-medium font-['Inter'] leading-relaxed"
      >
        Effortless Communication, Maximum Productivity
      </div>
    </div>
    <div
      class="w-[348px] text-center text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
    >
      Experience uninterrupted communication. Our servicie guarantees you won´t
      miss any calls or text, allowing you to focus on your work with complete
      confindence
    </div>
    <div class="justify-start items-center gap-5 inline-flex">
      <div class="w-12 h-12 relative">
        <img
          class="w-12 h-12 left-0 top-0 absolute"
          src="https://via.placeholder.com/48x48"
        />
      </div>
      <div class="w-12 h-12 relative">
        <img
          class="w-12 h-12 left-0 top-0 absolute"
          src="https://via.placeholder.com/48x48"
        />
      </div>
      <div class="w-12 h-12 relative">
        <img
          class="w-12 h-12 left-0 top-0 absolute"
          src="https://via.placeholder.com/48x48"
        />
      </div>
      <div class="w-12 h-12 relative">
        <img
          class="w-12 h-12 left-0 top-0 absolute"
          src="https://via.placeholder.com/48x48"
        />
      </div>
    </div>
    <div class="h-[46px] flex-col justify-start items-start flex">
      <div
        class="self-stretch text-[#052f47] text-base font-bold font-['Khula'] leading-relaxed"
      >
        Contact us:
      </div>
      <div
        class="self-stretch h-5 flex-col justify-start items-start gap-0.5 flex"
      >
        <div
          class="self-stretch text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
        >
          1.000.000.000
        </div>
      </div>
    </div>
    <div class="h-[46px] flex-col justify-start items-start flex">
      <div
        class="self-stretch text-[#052f47] text-base font-bold font-['Khula'] leading-relaxed"
      >
        Address:
      </div>
      <div
        class="self-stretch h-5 flex-col justify-start items-start gap-0.5 flex"
      >
        <div
          class="self-stretch text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
        >
          aaaaaa/aaaa/aaaaa/aaaaa
        </div>
      </div>
    </div>
    <div class="h-[74px] flex-col justify-start items-start flex">
      <div
        class="self-stretch text-[#052f47] text-base font-bold font-['Khula'] leading-relaxed"
      >
        Legal:
      </div>
      <div class="self-stretch h-12 flex-col justify-start items-start flex">
        <div class="w-[350px] h-12 relative">
          <div
            class="w-[350px] left-0 top-0 absolute text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
          >
            Términos y condiciones
          </div>
          <div
            class="w-[350px] left-0 top-[28px] absolute text-[#052f47]/60 text-base font-normal font-['Khula'] leading-tight"
          >
            Política de privacidad
          </div>
        </div>
      </div>
    </div>
    <div class="w-[360px] mix-blend-luminosity text-center">
      <span
        style="text-[#052f47] text-base font-normal font-['Khula'] leading-relaxed"
        >© 2024
      </span><span
        style="text-[#052f47] text-base font-extrabold font-['Inter'] leading-relaxed"
        >Towit</span
      ><span
        style="text-[#052f47] text-base font-normal font-['Khula'] leading-relaxed"
        >links·All Right Reserve</span
      >
    </div>
  </div>
</div>

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>
