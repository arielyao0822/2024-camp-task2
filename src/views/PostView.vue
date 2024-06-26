<template>
  <main>
    <section class="container pb-7 pt-lg-9 pb-lg-7 mt-lg-9">
      <div class="row flex-lg-row-reverse justify-content-lg-between pb-md-7">
        <div class="col-12 col-lg-3">
          <aside class="blog__menu px-3 py-4 p-lg-7 bg-primary-100">
            <ul class="d-flex flex-lg-column justify-content-md-center justify-content-lg-start gap-7 mb-0 p-xxl-7 list-unstyled">
              <li class="flex-shrink-0">
                <button class="blog__menu--active pb-1 fs-5 text-primary-600 link-primary-500 bg-transparent" type="button">全部文章</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 fs-5 text-primary-600 link-primary-500 bg-transparent border-0" type="button">UI/UX 新知</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 fs-5 text-primary-600 link-primary-500 bg-transparent border-0" type="button">數位產品設計</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 fs-5 text-primary-600 link-primary-500 bg-transparent border-0" type="button">平面設計</button>
              </li>
              <li class="flex-shrink-0">
                <button class="pb-1 fs-5 text-primary-600 link-primary-500 bg-transparent border-0" type="button">前端開發</button>
              </li>
            </ul>
          </aside>
        </div>
        <article class="col-12 col-lg-8 mt-9 mt-lg-0 mb-0 pt-9 pt-lg-0 text-primary-700">
          <nav class="mb-3 mb-lg-7" aria-label="breadcrumb">
            <ol class="breadcrumb">
              <li class="breadcrumb-item text-primary-500">
                <a class="text-primary-500 text-decoration-none" href="#">數位產品設計</a>
              </li>
              <li class="breadcrumb-item text-primary-500 active" aria-current="page">2023/09/20 發佈</li>
            </ol>
          </nav>
          <h1 class="mb-3 mb-lg-4 fs-2 text-center">虛擬實境 (VR) 介面設計對使用者沈浸感影響的研究</h1>
          <h4 class="mb-4 mb-lg-9 text-center fw-normal">- 探索虛擬實境技術的現狀與前景 -</h4>
          <p class="mb-6 mb-lg-7 fs-5">在當今數位科技的快速發展下，虛擬實境（VR）技術日益受到關注。VR技術為使用者提供了身臨其境的體驗，並在多個領域中得到應用，如遊戲、教育、醫療等。然而，要實現真正的沈浸感需要考慮多個因素，其中介面設計是至關重要的一環。本研究旨在探討不同介面設計對使用者在虛擬環境中的沈浸感的影響，以期為優化VR技術的使用者體驗提供參考。</p>
          <h2 class="mb-3 fs-4">大眾看法</h2>
          <p class="mb-6 mb-lg-7 fs-5">虛擬實境技術近年來受到越來越多人的關注和接受。人們對VR技術的潛力持樂觀態度，認為它能夠提供全新的體驗和娛樂方式，並在教育、訓練等領域中有著廣泛的應用前景。然而，也有一些人擔心虛擬實境技術的成熟度和可靠性，對其潛在風險抱有顧慮。</p>
          <h2 class="mb-3 fs-4">現行產品</h2>
          <p class="mb-6 mb-lg-7 fs-5">目前市面上有許多虛擬實境產品，如Vision Pro、Oculus Rift、HTC Vive、PlayStation VR等。這些產品在硬件性能、軟件支持和使用者體驗等方面存在差異，而介面設計是影響使用者體驗的重要因素之一。不同的介面設計可以影響使用者的操作方式、感知真實度以及沈浸感。</p>
          <div class="row row-gap-4 mb-6 mb-lg-7">
            <div class="col-12 col-lg-6 text-center">
              <figure class="figure mb-0">
                <img src="@/assets/images/vision-pro.png" class="figure-img img-fluid" alt="vision-pro">
                <figcaption class="figure-caption text-primary-600">Vision Pro</figcaption>
              </figure>
            </div>
            <div class="col-12 col-lg-6 text-center">
              <figure class="figure mb-0">
                <img src="@/assets/images/oculus-rift.png" class="figure-img img-fluid" alt="vision-pro">
                <figcaption class="figure-caption text-primary-600">Oculus Rift</figcaption>
              </figure>
            </div>
            <div class="col-12 col-lg-6 text-center">
              <figure class="figure mb-0">
                <img src="@/assets/images/htc-vive.png" class="figure-img img-fluid" alt="HTC Vive">
                <figcaption class="figure-caption text-primary-600">VHTC Vive</figcaption>
              </figure>
            </div>
            <div class="col-12 col-lg-6 text-center">
              <figure class="figure mb-0">
                <img src="@/assets/images/playstation-vr.png" class="figure-img img-fluid" alt="PlayStation VR">
                <figcaption class="figure-caption text-primary-600">PlayStation VR</figcaption>
              </figure>
            </div>
          </div>
          <h2 class="mb-3 fs-4">技術創新</h2>
          <p class="mb-6 mb-lg-7 fs-5">隨著硬件技術的不斷進步，VR設備的性能和功能也在不斷提升。高解析度的顯示器、感應器、追蹤技術等創新技術的應用，使得虛擬實境的感知和互動性能夠更加真實和流暢。然而，技術創新也帶來了一些挑戰，例如圖像質量、感知延遲等問題仍然存在，需要進一步解決。<br>技術瓶頸：儘管虛擬實境技術取得了巨大進步，但仍然存在一些技術瓶頸需要克服。例如，許多使用者報告在使用VR設備時出現眩暈和不適感，這與感知延遲和畫面模糊等問題有關。此外，虛擬實境的內容和應用也需要更多的創新和豐富，以滿足不同使用者的需求。</p>
          <h2 class="mb-3 fs-4">技術瓶頸</h2>
          <p class="mb-6 mb-lg-7 fs-5">儘管虛擬實境技術取得了巨大進步，但仍然存在一些技術瓶頸需要克服。例如，許多使用者報告在使用VR設備時出現眩暈和不適感，這與感知延遲和畫面模糊等問題有關。此外，虛擬實境的內容和應用也需要更多的創新和豐富，以滿足不同使用者的需求。</p>
          <h2 class="mb-3 fs-4">未來展望</h2>
          <p class="mb-6 mb-lg-7 fs-5">未來，虛擬實境技術將繼續向前發展。我們可以期待更加先進的硬件設備和更加豐富多彩的虛擬內容。同時，介面設計也將繼續演進，以提供更加直觀和便捷的操作方式，進一步增強使用者的沈浸感和參與感。總的來說，虛擬實境技術的未來是充滿希望和潛力的，我們期待著看到它在各個領域中的廣泛應用和發展。</p>
          <span>Noel 主筆</span>
        </article>
      </div>
    </section>

    <section class="container px-6 px-lg-0 pt-7 pb-7 pb-lg-9 mt-lg-7 mb-7 mb-lg-9 border-top border-primary-400">
      <h3 class="mb-7 text-center text-lg-start text-primary-700">相關文章</h3>
      <div class="row row-gap-5">
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0">
            <img src="@/assets/images/article-image1.png" class="card-img-top rounded-3" alt="article-1">
            <div class="card-body">
              <h5 class="card-title mb-3 text-primary-700">Vision Pro 登場！Vision Pro UI/UX 設計重點大公開 (上)</h5>
              <div class="d-flex justify-content-between align-items-center">
                <span class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">UI/UX 新知</span>
                <p class="card-text fs-6 text-primary-600"><small class="text-body-secondary">2024/02/10</small></p>
              </div>
              <a class="stretched-link" href="#"></a>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 col-lg-4">
          <div class="card border-0">
            <img src="@/assets/images/article-image7.png" class="card-img-top rounded-3" alt="article-7">
            <div class="card-body">
              <h5 class="card-title mb-3 text-primary-700">Vision Pro 來了！UIUX 設計師的未來在哪裡？</h5>
              <div class="d-flex justify-content-between align-items-center">
                <span class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4">UI/UX 新知</span>
                <p class="card-text fs-6 text-primary-600"><small class="text-body-secondary">2023/07/10</small></p>
              </div>
              <a class="stretched-link" href="#"></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>
</template>