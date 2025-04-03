---
layout: single
# title: 大江 
permalink: /myself
author_profile: true
description: "大江優真（Yuma Oe）のプロフィールです。"
---

<!-- # 大江 優真（Yuma Oe）

![profile](./assets/img/profile_main.jpg)

## JOB
College Student

## AGE
22

## MAJOR
Informatics -->

<div class="profile-container">
  <div class="profile-text">
    <h2>NAME</h2>
    <p>大江 優真（Yuma Oe）</p>
    <h2>JOB</h2>
    <p>Graduate Student</p>
    <h2>AGE</h2>
    <p>22</p>
    <h2>MAJOR</h2>
    <p>Informatics</p>
    <!-- 他の情報もここに追加 -->
  </div>
  <div class="profile-image">
    <img src="../assets/img/others/profile.jpg" alt="プロフィール写真" />
  </div>
</div>
<style>
  .profile-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  margin-top: 2rem;
  }

  .profile-text {
    flex-basis: 50%;
    padding-right: 2rem;
  }

  .profile-image {
    flex-basis: 50%;
    text-align: right;
  }

  .profile-image img {
    max-width: 150%;
    height: auto;
    <!-- border-radius: 10px; /* 写真の角を丸める場合 */ -->
  }

  @media (max-width: 768px) {
    .profile-container {
      flex-direction: column;
    }

    .profile-text {
      padding-right: 0;
      text-align: center;
    }

    .profile-image {
      text-align: center;
      margin-top: 1.5rem;
    }

    .profile-image img {
      max-width: 100%;
      height: auto;
    }
  }

</style>