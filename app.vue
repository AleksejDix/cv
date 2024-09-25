<template>
  <div class="page">
    <div class="container A4 bg-white rounded-lg">
      <header class="flex -mx-4">
        <div class="px-4 w-3/4">
          <Title>Aleksej Dix</Title>
          <h2 class="text-green-600 tracking-tight text-lg font-bold pb-2">
            Engineering Manager, Frontend Developer, Speaker, Teacher
          </h2>
          <div class="py-2 -mx-2 flex flex-wrap font-bold">
            <div class="w-1/2 px-2">
              <a href="mailto:privat@aleksejdix.com">privat@aleksejdix.com</a>
            </div>
            <div class="w-1/2 px-2">+41798634393</div>
            <div class="w-1/2 px-2">
              <a target="blank" rel="noopener" href="https://webzueri.ch"
                >https://webzueri.ch</a
              >
            </div>
            <div class="w-1/2 px-2">Männedorf, ZH, Switzerland</div>
          </div>
        </div>

        <div class="px-4 w-1/4">
          <Avatar />
        </div>
      </header>

      <main class="flex -mx-6">
        <div class="w-3/5 px-6">
          <section>
            <header class="pb-2 pt-4"><h3>Awards</h3></header>
            <Label>Best of Swiss Web - Innovation GOLD</Label>
            <Meta>2021 • propertycaptain.ch • Zurich, Switzerland</Meta>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Technical Skills</h3></header>
            <ul>
              <li>
                <Label>Expert in</Label>
                <Meta>
                  Vue.js, Tailwind CSS, Pinia, Vue Router, Nuxt.js, xState,
                  TamnStack Query, Web Components, Web Performance, Image
                  Optimization, Web Accessibility (WCAG), SEO, Typescript,
                  JavaScript, Web Security practices, Buildtools
                </Meta>
              </li>

              <li>
                <Label>Tools</Label>
                <Meta>
                  Jira, Confluence, Gitlab, Github, Sentry, Matomo, Google
                  Analytics, Google Search Console, Different Content Management
                  Systems, Adobe Creative Suite, Sketch, Figma, InVision,
                  Netlify, Vercel, Turborepo, Yarn, NPM, Azure,
                  Firebase/Firestore, Gitlab CI, Pipelines, SonarQube, Cypress,
                  Puppeteer, Browser Stack, Sauce Labs, Lighthouse, Webpagetest,
                  Pingdom, Speedcurve, Datadog, Trello, Asana, Slack, Zoom,
                  Google Meet, Microsoft Teams, VSCode
                </Meta>
              </li>
            </ul>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Experience</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li>
                <Label>Head of Frontend Development</Label>
                <Meta>
                  05.2023 - 02.2024 • Abacus Research AG • Zürich, Switzerland
                </Meta>
                <ul class="list-disc pl-6 pb-1 text-xs [&>*]:py-1 py-2">
                  <li>
                    Led the development of DeepSign, a critical system for
                    digital signatures, used across Swiss regions. Ensured high
                    availability, security, and performance under heavy loads.
                  </li>
                  <li>
                    Introduced automated CI/CD pipelines, dramatically improving
                    deployment speed and code reliability. Automated NPM package
                    releases to a private repository.
                  </li>
                  <li>
                    Integrated Sentry and Matomo for real-time error tracking
                    and performance monitoring, significantly improving code
                    quality and the user experience.
                  </li>
                  <li>
                    Managed a team of 8 Frontend Developers and 2 Designers,
                    successfully onboarding 6 new developers.
                  </li>
                  <li>
                    Analyzed and improved developer skill gaps through personal
                    training and targeted courses to boost team performance.
                  </li>
                  <li>
                    Organized weekly meetings for sharing news on tools and best
                    practices in frontend development, fostering a culture of
                    continuous learning.
                  </li>
                </ul>
              </li>
              <li>
                <Label>Head of Frontend Development</Label>
                <Meta>
                  05.2016 - 04.2023 • Avobis Group AG • Zürich, Switzerland
                </Meta>
                <ul class="list-disc pl-6 pb-1 text-xs [&>*]:py-1 py-2">
                  <li>
                    Led the development of immosparrow.ch, a platform to
                    visualize the Swiss real estate market. Reduced app load
                    time and bundle size by 50%.
                  </li>
                  <li>
                    Cut infrastructure costs from 20,000 CHF to a few hundred
                    per month, while managing 75GB daily traffic.
                  </li>
                  <li>
                    Built 3D tools for visualizing building shadows at different
                    times of day, enhancing the user experience.
                  </li>
                  <li>
                    Developed internal tools like eDossier to streamline real
                    estate data management. Migrated public-facing products like
                    propertycaptain.ch to Vue 3 and TypeScript.
                  </li>
                  <li>
                    Led a team of 10 Frontend Developers and 2 Automated Testing
                    Engineers, improving team collaboration and code quality.
                  </li>
                  <li>
                    Converted the design system to Tailwind CSS, improving UI
                    consistency and reducing component creation time.
                  </li>
                  <li>
                    Improved SEO by enabling Server-Side Rendering and
                    implemented lazy loading for images and components,
                    optimizing user experience.
                  </li>
                </ul>
              </li>
              <li>
                <Label>Manager, Principal Front-End Architect</Label>
                <Meta
                  >11.2016 - 04.2021 • oddEVEN AG • Zürich, Switzerland
                </Meta>
                <ul class="list-disc pl-6 pb-1 text-xs [&>*]:py-1 py-2">
                  <li>
                    Sanitas – sanitas.com: Developed a portal where employees
                    and doctors can manage insurance data and work on health
                    cases of patients. This internal tool greatly improved
                    efficiency across the company, enabling streamlined
                    management of medical cases, offers, contracts, and personal
                    data. Reduced the size of the legacy application by 90%,
                    significantly improving performance.
                  </li>
                  <li>
                    Created a D3.js library for large-scale data visualization,
                    used by Swiss Re to identify company connections and manage
                    payments, supporting mission-critical decisions.
                  </li>
                  <li>
                    Zurich Airport AG – zurich-airport.com: Developed a tool
                    using Vue.js that allows users to easily find stores,
                    services, and restaurants within the airport, enhancing the
                    overall customer experience by providing quick access to
                    essential information.
                  </li>
                  <li>
                    <strong>Zurich Insurance </strong> Leading the rebranding of
                    many products.
                  </li>
                  <li>
                    Zurich Insurance: Led the development of multiple products,
                    including the public websites Zurich Vita and Zurich
                    Insurance Invest. Created interactive charts for users to
                    track investment fund growth and calculate their future
                    pensions. Additionally, managed the entire rebranding
                    process for these products by launching new, modernized
                    websites, improving user experience and brand visibility.
                  </li>
                </ul>
              </li>
              <li>
                <Label>Senior Software Engineer</Label>
                <Meta>
                  11.2015 - 11.2016 • Siroop AG • Zurich, Switzerland
                </Meta>

                <ul class="list-disc pl-6 pb-1 text-xs [&>*]:py-1 py-2">
                  <li>Launched online marketplace siroop.ch</li>
                </ul>
              </li>
              <li>
                <Label>Senior Frontend Developer</Label>
                <Meta
                  >12.2014 – 10.2015 • Match it GmbH • Bielefeld, Germany</Meta
                >
              </li>
              <li>
                <Label>UX Design / Frontend Development</Label>
                <Meta>
                  04.2014 – 11.2014 • PaperC GmbH • Düsseldorf, Germany
                </Meta>
              </li>
              <li>
                <Label>Screen Design / Frontend Development</Label>
                <Meta
                  >08.2011 – 03.2014 • ShortCuts GmbH • Berlin, Germany
                </Meta>
              </li>
            </ul>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Education</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li>
                <Label>Mobile Web Specialist</Label>
                <Meta>2018 • Google, Online</Meta>
              </li>
              <li>
                <Label>Professional Scrum Developer</Label>
                <Meta> 06.2018 • Scrum HQ • Boston, USA </Meta>
              </li>
              <li>
                <Label>Designer of digital and print media</Label>
                <Meta
                  >02.2010 - 02.2013 • Cimdata Academy • Berlin, Germany</Meta
                >
              </li>
              <li>
                <Label>Technical assistant of informatics</Label>
                <Meta
                  >08.2004 - 06.2008 • Eugen Reintjes School • Hameln,
                  Germany</Meta
                >
              </li>
            </ul>
          </section>
        </div>

        <aside class="w-2/5 px-6">
          <section>
            <header class="pb-2 pt-4"><h3>Workshops</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li><Label>Fast Responsive Images</Label></li>
              <li><Label>CSS at Scale</Label></li>
              <li>
                <Label>Advanced Design Patterns for big Vue.js Apps</Label>
              </li>
              <li><Label>Building SPA with Vue.js</Label></li>
              <li><Label>How to restart in a new city</Label></li>
            </ul>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Community Work</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li>
                <Label>Vue.js Screencasts</Label>
                <Meta>
                  03.2019 - 08.2021 •
                  <a
                    href="https://vueschool.io/courses/reusable-vuejs-components-with-slots"
                    >vueschool.io</a
                  >
                </Meta>
              </li>
              <li>
                <Label>Vue.js Workshops</Label>
                <Meta>03.2019 - 08.2021 • Digicomp.ch</Meta>
              </li>
              <li>
                <Label>Frontend Best Practices</Label>
                <Meta>09.2019 - 03.2020 • OST Rapperswil</Meta>
              </li>
              <li>
                <Label>Teaching Vue.js at Digicomp.ch</Label>
                <Meta>03.2019 - 08.2021 • Zürich</Meta>
              </li>
              <li>
                <Label>Vue Zurich Meetup</Label>
                <Meta>02.2019 - Ongoing • Zürich</Meta>
              </li>
              <li>
                <Label>VueVixens Workshops</Label>
                <Meta>09.2019 • Zürich</Meta>
              </li>
              <li>
                <Label>Web Zurich Meetup</Label>
                <Meta>10.2016 - Ongoing</Meta>
              </li>
            </ul>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Public Speaking</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li>
                <Label>Vue.js Portals - UI Wormholes</Label>
                <Meta>03.2020 • Web Zurich Meetup • Zurich</Meta>
              </li>
              <li>
                <Label>Why we need Portals in Vue 3</Label>
                <Meta>01.2020 • Vue Basel Meetup • Basel</Meta>
              </li>
              <li>
                <Label>Vue.js apps without JavaScript</Label>
                <Meta>12.2019 • Google Webmaster Conference • Zurich</Meta>
              </li>
              <li>
                <Label>Vue.js apps without JavaScript</Label>
                <Meta>09.2019 • Vue.js Meetup • Zurich</Meta>
              </li>
              <li>
                <Label>Nuxt.js - Serverside Rendering</Label>
                <Meta>09.2019 • GraphQL Day • Konstanz</Meta>
              </li>
              <li>
                <Label>Vue.js - Component Composition</Label>
                <Meta>01.2019 • Vue.js Meetup • Zurich</Meta>
              </li>
              <li>
                <Label>Documentations with VuePress</Label>
                <Meta>06.2018 • Vue.js Meetup Day • Zurich</Meta>
              </li>
              <li>
                <Label>Do you even Grid?</Label>
                <Meta>10.2017 • Web Zurich Zurich</Meta>
              </li>
            </ul>
          </section>
          <section>
            <header class="pb-2 pt-4"><h3>Languages</h3></header>
            <ul class="divide-y divide-dashed divide-slate-200 [&>*]:py-1">
              <li>
                <Label>German (Native)</Label>
              </li>
              <li><Label>English (B2)</Label></li>
              <li><Label>Russian (Native)</Label></li>
              <li><Label>Ukrainian (Native)</Label></li>
            </ul>
          </section>
        </aside>
      </main>
    </div>
  </div>
</template>

<script setup>
import Title from "@/components/Title.vue";
import Avatar from "@/components/Avatar.vue";
import Label from "@/components/Label.vue";
import Meta from "@/components/Meta.vue";
</script>

<style scoped>
.A4 {
  @apply shadow;
  padding: 1.5cm;
  max-width: 21cm;
  margin: 0 auto;
}
</style>
