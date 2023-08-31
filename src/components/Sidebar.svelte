<svelte:head>
  <link rel="stylesheet" href="https://unpkg.com/mono-icons@1.0.5/iconfont/icons.css" >
</svelte:head>

<script>
</script>

<style>
    .sidebar-container {
      position: fixed;
      top: 50%;
      right: 30px;
      transform: translateY(-50%);
      width: 50px;
      border-radius: 20px;
      background-color: #F0B86E;
      z-index: 10;
    }

    .sidebar {
      padding: 10px;
    }

    .space {
      padding: 6px 0;
    }

    .sidebar-container .space a:hover svg path {
      fill: white;
    }
  </style>

  <div class="sidebar-container">
    <div class="sidebar">
      <div class="space">
        <a href="/">
          <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg">
            <path xmlns="http://www.w3.org/2000/svg" d="M11.3356 2.25259C11.7145 1.9158 12.2855 1.9158 12.6644 2.25259L21.6644 10.2526C22.0772 10.6195 22.1143 11.2516 21.7474 11.6644C21.3805 12.0771 20.7484 12.1143 20.3356 11.7474L20 11.4491V19C20 20.1046 19.1046 21 18 21H6.00001C4.89544 21 4.00001 20.1046 4.00001 19V11.4491L3.66437 11.7474C3.25159 12.1143 2.61952 12.0771 2.2526 11.6644C1.88568 11.2516 1.92286 10.6195 2.33565 10.2526L11.3356 2.25259ZM6.00001 9.67129V19H9.00001V14C9.00001 13.4477 9.44773 13 10 13H14C14.5523 13 15 13.4477 15 14V19H18V9.67129L12 4.33795L6.00001 9.67129ZM13 19V15H11V19H13Z" fill="#0D0D0D"></path>
          </svg>
        </a>
      </div>
      <div class="space">
        <a href="/about">
          <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg">
            <path xmlns="http://www.w3.org/2000/svg" d="M12 4C9.79086 4 8 5.79086 8 8C8 10.2091 9.79086 12 12 12C14.2091 12 16 10.2091 16 8C16 5.79086 14.2091 4 12 4ZM6 8C6 4.68629 8.68629 2 12 2C15.3137 2 18 4.68629 18 8C18 11.3137 15.3137 14 12 14C8.68629 14 6 11.3137 6 8ZM8 18C6.34315 18 5 19.3431 5 21C5 21.5523 4.55228 22 4 22C3.44772 22 3 21.5523 3 21C3 18.2386 5.23858 16 8 16H16C18.7614 16 21 18.2386 21 21C21 21.5523 20.5523 22 20 22C19.4477 22 19 21.5523 19 21C19 19.3431 17.6569 18 16 18H8Z" fill="#0D0D0D"></path>
          </svg>
        </a>
      </div>
      <div class="space">
        <a href="/projects">
          <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg">
            <path xmlns="http://www.w3.org/2000/svg" d="M2 5C2 3.89543 2.89543 3 4 3H20C21.1046 3 22 3.89543 22 5V7C22 7.74708 21.5904 8.39848 20.9835 8.74188C20.9944 8.82638 21 8.91253 21 9V19C21 20.1046 20.1046 21 19 21H5C3.89543 21 3 20.1046 3 19V9C3 8.91253 3.00561 8.82638 3.0165 8.74188C2.40961 8.39848 2 7.74707 2 7V5ZM20 7V5H4V7H20ZM5 9V19H19V9H5ZM8 12C8 11.4477 8.44772 11 9 11H15C15.5523 11 16 11.4477 16 12C16 12.5523 15.5523 13 15 13H9C8.44772 13 8 12.5523 8 12Z" fill="#0D0D0D"></path>
          </svg>
        </a>
      </div>
      <div class="space">
        <a href="/contact">
          <svg fill="none" viewBox="0 0 24 24" height="24" width="24" xmlns="http://www.w3.org/2000/svg">
            <path xmlns="http://www.w3.org/2000/svg" d="M8 8C5.75228 8 4 9.75228 4 12C4 14.2477 5.75228 16 8 16H10C10.5523 16 11 16.4477 11 17C11 17.5523 10.5523 18 10 18H8C4.64772 18 2 15.3523 2 12C2 8.64772 4.64772 6 8 6H10C10.5523 6 11 6.44772 11 7C11 7.55228 10.5523 8 10 8H8ZM13 7C13 6.44772 13.4477 6 14 6H16C19.3523 6 22 8.64772 22 12C22 15.3523 19.3523 18 16 18H14C13.4477 18 13 17.5523 13 17C13 16.4477 13.4477 16 14 16H16C18.2477 16 20 14.2477 20 12C20 9.75228 18.2477 8 16 8H14C13.4477 8 13 7.55228 13 7ZM7 12C7 11.4477 7.44772 11 8 11H16C16.5523 11 17 11.4477 17 12C17 12.5523 16.5523 13 16 13H8C7.44772 13 7 12.5523 7 12Z" fill="#0D0D0D"></path>
          </svg>
        </a>
      </div>
    </div>
  </div>