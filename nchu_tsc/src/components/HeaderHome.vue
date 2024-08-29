<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
      <div class="container-fluid">
        <a class="navbar-brand" href="/">
          <img src="/favicon.ico" alt="家教服務社" width="40" height="40" class="d-inline-block align-middle" />
          <span class="align-middle">家教服務社</span>
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#" role="button">最新公告</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                學生
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">入社</a></li>
                <li><hr class="dropdown-divider" /></li>
                <li><a class="dropdown-item" href="#">申請接案</a></li>
                <li><a class="dropdown-item" href="#">回報狀態</a></li>
              </ul>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                家長
              </a>
              <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">新增案件</a></li>
              </ul>
            </li>
          </ul>
  
          <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="#">登入</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">註冊</a>
            </li>
          </ul>
          <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
        </div>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'HeaderHome',
  };
  </script>
  
  <style scoped>
  /* 這裡可以添加特定於這個組件的樣式 */
  </style>
  