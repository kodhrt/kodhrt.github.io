---
layout: single
# title: 大江 
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
    <p>College Student</p>
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
  padding: 1rem; /* ページ全体に余白を追加 */
}

.profile-text {
  flex-basis: 50%; /* PCでは50%幅 */
  padding-right: 2rem;
  font-size: 1.2rem; /* 基本のフォントサイズ */
}

.profile-text h2 {
  font-size: 1.5rem; /* 見出しサイズ */
}

.profile-image {
  flex-basis: 50%; /* PCでは50%幅 */
  text-align: right;
}

.profile-image img {
  max-width: 100%;
  height: auto;
  border-radius: 10px; /* 角を少し丸める */
}

/* モバイル対応 */
@media (max-width: 768px) {
  .profile-container {
    flex-direction: column; /* 縦並びにする */
    text-align: center; /* 中央揃え */
  }

  .profile-text {
    flex-basis: 100%; /* 幅を100%にする */
    padding-right: 0;
    font-size: 1rem; /* フォントサイズを小さく調整 */
  }

  .profile-image {
    flex-basis: 100%; /* 幅を100%にする */
    margin-top: 1rem; /* 上部に余白を追加 */
    text-align: center;
  }

  .profile-image img {
    max-width: 80%; /* モバイルでは少し小さく */
  }
}

/* タブレット対応 */
@media (max-width: 1024px) {
  .profile-container {
    padding: 1rem;
  }

  .profile-text {
    font-size: 1.1rem;
  }

  .profile-image img {
    max-width: 90%; /* 画像を少し大きめに */
  }
}


</style>