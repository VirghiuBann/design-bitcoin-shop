<template>
  <div>
    <div class="flex justify-center py-8">
      <button>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          height="24px"
          viewBox="0 0 24 24"
          width="24px"
          class="fill-current text-purple-500 h-12 w-12"
        >
          <path
            d="m12 5.32 6 3.37v6.62l-6 3.37-6-3.37V8.69l6-3.37m9 11.18c0 .38-.21.71-.53.88l-7.9 4.44c-.16.12-.36.18-.57.18-.21 0-.41-.06-.57-.18l-7.9-4.44A.991.991 0 0 1 3 16.5v-9c0-.38.21-.71.53-.88l7.9-4.44c.16-.12.36-.18.57-.18.21 0 .41.06.57.18l7.9 4.44c.32.17.53.5.53.88v9M12 4.15 5 8.09v7.82l7 3.94 7-3.94V8.09l-7-3.94Z"
          />
        </svg>
      </button>
    </div>

    <div class="flex flex-col items-center py-4">
      <!-- apps -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24px"
            viewBox="0 0 24 24"
            width="24px"
            fill="#000000"
            class="fill-current text-gray-400"
          >
            <path d="M0 0h24v24H0V0z" fill="none" />
            <path
              d="M16.66 4.52l2.83 2.83-2.83 2.83-2.83-2.83 2.83-2.83M9 5v4H5V5h4m10 10v4h-4v-4h4M9 15v4H5v-4h4m7.66-13.31L11 7.34 16.66 13l5.66-5.66-5.66-5.65zM11 3H3v8h8V3zm10 10h-8v8h8v-8zm-10 0H3v8h8v-8z"
            />
          </svg>
        </a>
      </div>
      <!-- stats -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            width="24"
            class="fill-current text-gray-400"
          >
            <path d="M0 0h24v24H0V0z" fill="none" />
            <path
              d="M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2zm0 16H5V5h14v14zM7 10h2v7H7zm4-3h2v10h-2zm4 6h2v4h-2z"
            />
          </svg>
        </a>
      </div>
      <!-- list -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            width="24"
            class="fill-current text-gray-400"
          >
            <path d="M0 0h24v24H0V0z" fill="none" />
            <path
              d="M11 7h6v2h-6zm0 4h6v2h-6zm0 4h6v2h-6zM7 7h2v2H7zm0 4h2v2H7zm0 4h2v2H7zM20.1 3H3.9c-.5 0-.9.4-.9.9v16.2c0 .4.4.9.9.9h16.2c.4 0 .9-.5.9-.9V3.9c0-.5-.5-.9-.9-.9zM19 19H5V5h14v14z"
            />
          </svg>
        </a>
      </div>

      <!-- calendar -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            class="fill-current text-gray-400"
          >
            <path
              d="M19 3h-1V1h-2v2H8V1H6v2H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h9c-.6-.5-1.1-1.2-1.5-2H5V9h14v1.6c.7.1 1.4.3 2 .7V5c0-1.1-.9-2-2-2m0 4H5V5h14m-1 7.5c1.1 0 2.1.4 2.8 1.2l1.2-1.2v4h-4l1.8-1.8c-.5-.4-1.1-.7-1.8-.7-1.4 0-2.5 1.1-2.5 2.5S16.6 19 18 19c.8 0 1.5-.4 2-1h1.7c-.6 1.5-2 2.5-3.7 2.5-2.2 0-4-1.8-4-4s1.8-4 4-4Z"
            />
          </svg>
        </a>
      </div>
      <!-- percents -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            class="fill-current text-gray-400"
          >
            <path
              d="M20.04 8.71V4h-4.7L12 .69 8.71 4H4v4.71L.69 12 4 15.34v4.7h4.71L12 23.35l3.34-3.31h4.7v-4.7L23.35 12l-3.31-3.29M8.83 7.05c.98 0 1.77.79 1.77 1.78a1.77 1.77 0 0 1-1.77 1.77c-.99 0-1.78-.79-1.78-1.77 0-.99.79-1.78 1.78-1.78M15.22 17c-.98 0-1.77-.8-1.77-1.78a1.77 1.77 0 0 1 1.77-1.77c.98 0 1.78.79 1.78 1.77A1.78 1.78 0 0 1 15.22 17m-6.72.03L7 15.53 15.53 7l1.5 1.5-8.53 8.53Z"
            />
          </svg>
        </a>
      </div>
      <!-- query stats -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            width="24"
            class="fill-current text-gray-400"
          >
            <path fill="none" d="M0 0h24v24H0z" />
            <path
              d="M19.88 18.47c.44-.7.7-1.51.7-2.39 0-2.49-2.01-4.5-4.5-4.5s-4.5 2.01-4.5 4.5 2.01 4.5 4.49 4.5c.88 0 1.7-.26 2.39-.7L21.58 23 23 21.58l-3.12-3.11zm-3.8.11a2.5 2.5 0 0 1 0-5 2.5 2.5 0 0 1 0 5zm-.36-8.5c-.74.02-1.45.18-2.1.45l-.55-.83-3.8 6.18-3.01-3.52-3.63 5.81L1 17l5-8 3 3.5L13 6l2.72 4.08zm2.59.5c-.64-.28-1.33-.45-2.05-.49L21.38 2 23 3.18l-4.69 7.4z"
            />
          </svg>
        </a>
      </div>
      <!-- notifications -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            width="24"
            class="fill-current text-gray-400"
          >
            <path d="M0 0h24v24H0V0z" fill="none" />
            <path
              d="M12 22c1.1 0 2-.9 2-2h-4c0 1.1.9 2 2 2zm6-6v-5c0-3.07-1.63-5.64-4.5-6.32V4c0-.83-.67-1.5-1.5-1.5s-1.5.67-1.5 1.5v.68C7.64 5.36 6 7.92 6 11v5l-2 2v1h16v-1l-2-2zm-2 1H8v-6c0-2.48 1.51-4.5 4-4.5s4 2.02 4 4.5v6z"
            />
          </svg>
        </a>
      </div>
      <!-- settings -->
      <div class="btn__sidebar_items">
        <a href="#">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            height="24"
            width="24"
            class="fill-current text-gray-400"
          >
            <path d="M0 0h24v24H0V0z" fill="none" />
            <path
              d="M19.43 12.98c.04-.32.07-.64.07-.98 0-.34-.03-.66-.07-.98l2.11-1.65c.19-.15.24-.42.12-.64l-2-3.46a.5.5 0 0 0-.61-.22l-2.49 1c-.52-.4-1.08-.73-1.69-.98l-.38-2.65A.488.488 0 0 0 14 2h-4c-.25 0-.46.18-.49.42l-.38 2.65c-.61.25-1.17.59-1.69.98l-2.49-1a.566.566 0 0 0-.18-.03c-.17 0-.34.09-.43.25l-2 3.46c-.13.22-.07.49.12.64l2.11 1.65c-.04.32-.07.65-.07.98 0 .33.03.66.07.98l-2.11 1.65c-.19.15-.24.42-.12.64l2 3.46a.5.5 0 0 0 .61.22l2.49-1c.52.4 1.08.73 1.69.98l.38 2.65c.03.24.24.42.49.42h4c.25 0 .46-.18.49-.42l.38-2.65c.61-.25 1.17-.59 1.69-.98l2.49 1c.06.02.12.03.18.03.17 0 .34-.09.43-.25l2-3.46c.12-.22.07-.49-.12-.64l-2.11-1.65zm-1.98-1.71c.04.31.05.52.05.73 0 .21-.02.43-.05.73l-.14 1.13.89.7 1.08.84-.7 1.21-1.27-.51-1.04-.42-.9.68c-.43.32-.84.56-1.25.73l-1.06.43-.16 1.13-.2 1.35h-1.4l-.19-1.35-.16-1.13-1.06-.43c-.43-.18-.83-.41-1.23-.71l-.91-.7-1.06.43-1.27.51-.7-1.21 1.08-.84.89-.7-.14-1.13c-.03-.31-.05-.54-.05-.74s.02-.43.05-.73l.14-1.13-.89-.7-1.08-.84.7-1.21 1.27.51 1.04.42.9-.68c.43-.32.84-.56 1.25-.73l1.06-.43.16-1.13.2-1.35h1.39l.19 1.35.16 1.13 1.06.43c.43.18.83.41 1.23.71l.91.7 1.06-.43 1.27-.51.7 1.21-1.07.85-.89.7.14 1.13zM12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4 4-1.79 4-4-1.79-4-4-4zm0 6c-1.1 0-2-.9-2-2s.9-2 2-2 2 .9 2 2-.9 2-2 2z"
            />
          </svg>
        </a>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
