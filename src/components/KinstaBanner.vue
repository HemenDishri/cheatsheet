<template>
  <base-banner storage-key-name="kinsta-banner">
    <!-- mobile banner -->
    <template #shortMsg>
      <a
        class="mx-auto px-2 py-1"
        href="https://kinsta.com/application-hosting/?utm_source=pythoncheatsheet&utm_medium=digital&utm_campaign=python-hosting&utm_content=banner"
        rel="noreferrer"
      >
        <img
          src="/sponsors/kinsta/SVG/kinsta-mobile.png"
          loading="lazy"
          alt="Deploys by Kinsta"
          height="5"
        />
      </a>
    </template>

    <!-- sm and up banner -->
    <template #message>
      <!-- logo -->
      <a
        href="https://kinsta.com/application-hosting/?utm_source=pythoncheatsheet&utm_medium=digital&utm_campaign=python-hosting&utm_content=banner"
        rel="noreferrer"
      >
        <img
          class="hidden lg:flex"
          src="/sponsors/kinsta/SVG/PythonCheatSheet_banner_kinsta_logo.svg"
          loading="lazy"
          alt="Deploys by Kinsta"
        />
      </a>

      <!-- md banner -->
      <a
        href="https://kinsta.com/application-hosting/?utm_source=pythoncheatsheet&utm_medium=digital&utm_campaign=python-hosting&utm_content=banner"
        rel="noreferrer"
      >
        <img
          class="hidden md:block"
          src="/sponsors/kinsta/SVG/PythonCheatSheet_banner_Text.svg"
          loading="lazy"
          alt="Deploys by Kinsta"
        />
      </a>

      <!-- banner action -->
      <a
        href="https://kinsta.com/application-hosting/?utm_source=pythoncheatsheet&utm_medium=digital&utm_campaign=python-hosting&utm_content=banner"
        rel="noreferrer"
      >
        <img
          class="hidden lg:flex"
          src="/sponsors/kinsta/SVG/PythonCheatSheet_banner_button-main.svg"
          loading="lazy"
          alt="Deploys by Kinsta"
        />
      </a>
    </template>
  </base-banner>
</template>
