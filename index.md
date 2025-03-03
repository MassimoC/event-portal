---
layout: default
---

<div class="bg-gray-900">
    <main>
      <!-- Hero section -->
      <div class="relative isolate overflow-hidden">
        <svg class="absolute inset-0 -z-10 h-full w-full stroke-white/10 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
          <defs>
            <pattern id="983e3e4c-de6d-4c3f-8d64-b9761d1534cc" width="200" height="200" x="50%" y="-1" patternUnits="userSpaceOnUse">
              <path d="M.5 200V.5H200" fill="none" />
            </pattern>
          </defs>
          <svg x="50%" y="-1" class="overflow-visible fill-gray-800/20">
            <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
          </svg>
          <rect width="100%" height="100%" stroke-width="0" fill="url(#983e3e4c-de6d-4c3f-8d64-b9761d1534cc)" />
        </svg>
        <div class="absolute left-[calc(50%-4rem)] top-10 -z-10 transform-gpu blur-3xl sm:left-[calc(50%-18rem)] lg:left-48 lg:top-[calc(50%-30rem)] xl:left-[calc(50%-24rem)]" aria-hidden="true">
          <div class="aspect-[1108/632] w-[69.25rem] bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-20" style="clip-path: polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)"></div>
          </div>
        </div>
        <div class="mx-auto max-w-7xl px-6 pb-24 sm:pb-40 lg:flex lg:px-8 ">
          <div class="mx-auto max-w-2xl flex-shrink-0 lg:mx-0  lg:pt-8">   
          <img src="images/Logo-trans Small.png" alt="GDEX">        
            <div class="mt-24 sm:mt-32 lg:mt-16">
              <a href="#" class="inline-flex space-x-6">
                <span class="rounded-full bg-indigo-500/10 px-3 py-1 text-xl font-semibold leading-6 text-indigo-400 ring-1 ring-inset ring-indigo-500/20">15 June, 2024</span>                
              </a>
            </div>
            <h1 class="mt-10 text-4xl font-bold tracking-tight text-white sm:text-6xl">Join the Global DevOps Experience on June 15,&nbsp;2024!</h1>
            <p class="mt-6 text-lg leading-8 text-gray-300">Welcome to the <span class="font-bold tracking-tight text-white">Global DevOps Experience</span>, a unique, global event where the worlds of DevOps, Platform Engineering, and Developer Experience (DevEx) come together. </p>
             <p class="mt-6 text-lg leading-8 text-gray-300">This one-day event will be hosted by many venues all over the world and is more than an event. It is an experience. You will be part of a team in a fictious company, Globoticket, and help them to overcome some difficult and relevant challenges in the field of Platform Engineering, DevOps and Software Development. The event is centered around GitHub and Azure and AI and is the first global GitHub community event!</p>
            <div class="mt-10 flex items-center gap-x-6">
              <a href="#participants" class="rounded-md bg-indigo-500 px-3.5 py-2.5 text-sm font-semibold text-white shadow-sm hover:bg-indigo-400 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-400">Register as participant</a>
              <a href="{{ '/register' | relative_url }}" class="text-sm font-semibold leading-6 text-white">Register your venue <span aria-hidden="true">→</span></a>
            </div>
          </div>
          <div class="mx-auto mt-16 flex max-w-2xl sm:mt-24 lg:ml-10 lg:mr-0 lg:mt-0 lg:max-w-none lg:flex-none xl:ml-32">
            <div class="max-w-3xl flex-none sm:max-w-5xl lg:max-w-none">
               <div id="globeViz"  class="w-[76rem]"></div>
            </div>
          </div>
        </div> 
      <!-- Logo cloud -->
      <div class="mx-auto mt-8 max-w-7xl px-6 sm:mt-16 lg:px-8">
        <h2 class="text-center text-lg font-semibold leading-8 text-white">This event is sponsored by</h2>
        <div class="mx-auto mt-10 grid max-w-lg grid-cols-3 items-center gap-x-8 gap-y-10 sm:max-w-xl sm:grid-cols-2 sm:gap-x-10 lg:mx-0 lg:max-w-none lg:grid-cols-3">
          <!-- Loop through the site.data.sponsors -->
          {% for sponsor in site.data.sponsors %}
          <img class="col-span-2 max-h-12 w-full object-contain lg:col-span-1" src="{{ sponsor.logo }}" alt="{{ sponsor.name }}" width="158" height="48">
          {% endfor %}   
        </div>
      </div>
      <!-- Feature section -->
      <div class="mx-auto mt-32 max-w-7xl px-6 sm:mt-26 lg:px-8" id="more">
        <div class="mx-auto  text-center">
          <h2 class="text-base font-semibold leading-7 text-indigo-400">What is the GDEX</h2>
          <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl">The story</p>
          <p class="mt-6 text-lg leading-8 text-gray-300 text-justify">In 2017 the makers of GDEX created the <a href="https://globaldevopsbootcamp.com">Global DevOps Bootcamp</a> which was held in 2019 for the last time. In 2019 GDBC had 10.000 people joining the event in 92 venues in 32 countries all over the world. A true global community event. 
          </p>
          <p class="mt-6 text-lg leading-8 text-gray-300 text-justify">The Global DevOps experience follows a similar concept. The Global DevOps Experience is an "Event out of the box" and follows the sun. We will start in New Zealand and will end the event 36 hours later in Seattle. This means you can join anywhere and get the same experience! 
          </p>
        </div>
      </div>
      <!-- Current venues -->
       <div class="mx-auto mt-32 max-w-7xl px-6 sm:mt-26 lg:px-8" id="participants">
        <div class="mx-auto lg:mx-0 ">
          <!-- <h2 class="text-base font-semibold leading-8 text-indigo-400">Already registered venues</h2> -->
          <p class="mt-2 text-3xl font-bold tracking-tight text-white sm:text-4xl">How do I participate!</p>
          <p class="mt-6 text-lg leading-8 text-gray-300">On this page you can find a list of all venues that are registered around the world. Find a venue nearby and sign up at this venue to join the event! Don't see a venue nearby? Find a local DevOps community and ask them to host the event, or <a href="register" class="text-sm font-semibold leading-6 text-white">host</a> an event yourself.</p>
        </div>
        <div id="map" class="mt-8" style="height: 680px;"></div>
        <div class="">
          <div class="mt-8 flow-root">
            <div class="-mx-4 -my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
              <div class="inline-block min-w-full py-2 align-middle sm:px-6 lg:px-8">
                <table class="min-w-full">
                  <thead class="bg-gray-900">
                    <tr>
                      <th scope="col" class="py-3.5 pl-4 pr-3 text-left text-sm font-semibold text-white sm:pl-0">Name</th>
                      <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-white">Organizer</th>
                      <th scope="col" class="px-3 py-3.5 text-left text-sm font-semibold text-white">City</th>
                    </tr>
                  </thead>
                  {% assign grouped_venues = site.venues | group_by: "location.country" %}
                  {% for country in grouped_venues %}
                    {% assign visible_venues = country.items | where: "isShown", true %}
                    {% if visible_venues.size > 0 %}
                      <tbody class="bg-gray-900">
                        <tr class="border-gray-800">
                          <th colspan="5" scope="colgroup" class="bg-gray-900 py-2 pl-4 pr-3 text-left text-xl font-semibold text-white sm:pl-3">{{ country.name }}</th>
                        </tr>
                        {% for venue in visible_venues %}
                          <tr class="border-t border-gray-800">
                            <td class="whitespace-nowrap py-4 pl-4 pr-3 text-sm font-medium text-white sm:pl-3">
                              <a href="{{ venue.url }}">{{ venue.venueName }}</a>
                            </td>
                            <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-300">{{ venue.primaryContactName}}</td>
                            <td class="whitespace-nowrap px-3 py-4 text-sm text-gray-300">{{ venue.location.city}}</td>
                          </tr>
                        {% endfor %}
                      </tbody>
                    {% endif %}
                  {% endfor %}
                </table>
              </div>
            </div>
          </div>
        </div>
      </div> 
      <!-- CTA section -->
      <div class="relative isolate mt-4 px-6 py-32 sm:mt-16 sm:py-40 lg:px-8">
        <svg class="absolute inset-0 -z-10 h-full w-full stroke-white/10 [mask-image:radial-gradient(100%_100%_at_top_right,white,transparent)]" aria-hidden="true">
          <defs>
            <pattern id="1d4240dd-898f-445f-932d-e2872fd12de3" width="200" height="200" x="50%" y="0" patternUnits="userSpaceOnUse">
              <path d="M.5 200V.5H200" fill="none" />
            </pattern>
          </defs>
          <svg x="50%" y="0" class="overflow-visible fill-gray-800/20">
            <path d="M-200 0h201v201h-201Z M600 0h201v201h-201Z M-400 600h201v201h-201Z M200 800h201v201h-201Z" stroke-width="0" />
          </svg>
          <rect width="100%" height="100%" stroke-width="0" fill="url(#1d4240dd-898f-445f-932d-e2872fd12de3)" />
        </svg>
        <div class="absolute inset-x-0 top-10 -z-10 flex transform-gpu justify-center overflow-hidden blur-3xl" aria-hidden="true">
          <div class="aspect-[1108/632] w-[69.25rem] flex-none bg-gradient-to-r from-[#80caff] to-[#4f46e5] opacity-20" style="clip-path: polygon(73.6% 51.7%, 91.7% 11.8%, 100% 46.4%, 97.4% 82.2%, 92.5% 84.9%, 75.7% 64%, 55.3% 47.5%, 46.5% 49.4%, 45% 62.9%, 50.3% 87.2%, 21.3% 64.1%, 0.1% 100%, 5.4% 51.1%, 21.4% 63.9%, 58.9% 0.2%, 73.6% 51.7%)"></div>
        </div>
        <div class="mx-auto max-w-7xl text-center px-6 sm:mt-26 lg:px-8">
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">What do I need to do to host a venue</h2>
          <p class="mx-auto mt-6  text-lg leading-8 text-justify text-gray-300">Well, since GDEX is an event-out-of-the-box, you need to arrange a venue, some lunch and some people with a community ❤️ that can help proctoring GitHub, Azure and the challenges. Don't worry! We, the organizers, provide you, the local venue, with everything you need to run a high-value community event. We provide the presentations, the hands-on labs, the infrastructure, and a fun narrative for the day. We also provide instructions around the challenges and how to proctor these. </p>
          <p class="mx-auto mt-6  text-lg leading-8 text-justify text-gray-300">
 Interested? Please sign up and provide us with some basic details, and we will be in touch to help you set everything up.</p>
          <div class="mt-10 flex items-center justify-center gap-x-6">
            <a href="{{ '/register' | relative_url }}" class="rounded-md bg-white px-3.5 py-2.5 text-sm font-semibold text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white">Register your venue</a>
            <a href="#more" class="text-sm font-semibold leading-6 text-white">Learn more <span aria-hidden="true">→</span></a>
          </div>
        </div>
      </div>
    </main>
  </div>
  <script>

{% assign maxR = "20" %}
{% assign propagationSpeed = "20" %}
{% assign repeatPeriod = "2000"  %}

    const gData = [
    {% for venue in site.venues %}
      {% if venue.isShown %}
        {% assign lat = venue.location.latitude | plus: 0 %}
        {% assign lng = venue.location.longitude | plus: 0 %}
        {% if lat and lng %}
          {
            name: '{{ venue.venueName }}',
            organizer: '{{ venue.primaryContactName }}',
            url: '{{ venue.url }}',
            lat: {{ lat }},
            lng: {{ lng }},
            maxR: {{ maxR }},
            propagationSpeed: {{ propagationSpeed }},
            repeatPeriod: {{ repeatPeriod }}
          },
        {% endif %}
      {% endif %}
    {% endfor %}
    ];
 

    const colorInterpolator = t => `rgba(255,100,50,${Math.sqrt(1-t)})`;

  const myGlobe = Globe()
    (document.getElementById('globeViz'))

   // .globeImageUrl('images/worldmap.png')
    .globeImageUrl('//unpkg.com/three-globe/example/img/earth-blue-marble.jpg')
    .pointOfView({ lat: 40.178873, lng: -258.222656, altitude: 1 }) 
    .showGraticules(false)
    .showAtmosphere(true)
    .backgroundColor('rgba(0,0,0,0)')
    .showGlobe(true)
    .ringsData(gData)
    .ringColor(() => colorInterpolator)
    .ringMaxRadius('maxR')
    .ringPropagationSpeed('propagationSpeed')
    .ringRepeatPeriod('repeatPeriod')
    .labelsData(gData)
    .labelLat(d => d.lat)
    .labelLng(d => d.lng)
    .labelText(d => d.name)
   // .labelSize(d => Math.sqrt(d.properties.pop_max) * 4e-4)
    //.labelDotRadius(d => Math.sqrt(d.properties.pop_max) * 4e-4)
    .labelColor(() => 'rgba(255, 165, 0, 0.75)')
    .labelResolution(2); 

    myGlobe.controls().autoRotate = true;
    myGlobe.controls().autoRotateSpeed = 1.8;
    myGlobe.controls().enableZoom = true;

   // Map
   var map = L.map('map').setView([51.505, -0.09], 2); 
   L.tileLayer('https://tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
    attribution: '&copy; <a href="http://www.openstreetmap.org/copyright">OpenStreetMap</a>'
    }).addTo(map);

    // Add markers for each venue
    for (var i = 0; i < gData.length; i++) {
      var venue = gData[i];
      var marker = L.marker([venue.lat, venue.lng], {title: venue.name});
      
      // Bind a popup with the venue's name and URL to the marker
      marker.bindPopup(`Visit <a href="${venue.url}" target="_blank" rel="noopener noreferrer">${venue.name}</a> by ${venue.organizer}`);
      
      // Add the marker to the map
      marker.addTo(map);
    }
</script>
