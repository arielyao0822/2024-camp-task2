<script setup>
const collections = [
  {
    id: 1,
    name: '星際旅行訂票平台',
    description: '悠遊宇宙的夢想，從這裡開始實現',
    tags: ['網頁設計', '響應式設計', 'Bootstrap']
  },
  {
    id: 2,
    name: '理財App',
    description: '連動帳戶與行動支付，讓 AI 提供您最好的理財建議',
    tags: ['APP設計', 'iOS', 'React']
  },
  {
    id: 3,
    name: '醫美診所官網',
    description: '永保青春的秘密，從粹究開始',
    tags: ['網頁設計', '響應式設計', 'ＷordPress']
  },
  {
    id: 4,
    name: '美美美早餐店 POS 機 UI Design',
    description: '訂單送單一目瞭然，自動報表分析好輕鬆',
    tags: ['UI 設計', '前端開發', 'Wix']
  },
  {
    id: 5,
    name: '電影院訂票系統',
    description: '三步驟完成訂票，電腦手機都支援',
    tags: ['前端開發', '後端支援', 'Vue']
  },
  {
    id: 6,
    name: '巧克巧克形象官網設計',
    description: '三步驟完成訂票，電腦手機都支援',
    tags: ['UI設計', '設計系統', '網路電商']
  },
];

const importImage = (num) => {
  const image = new URL(`../assets/images/work-image${num}.png`, import.meta.url);
  return image.href;
};

</script>

<template>
  <main>
    <div class="bg-primary-100 pt-9 pb-7">
      <div class="container">
        <div class="row">
          <div class="col-12 col-md-10 col-lg-6 offset-md-1 offset-lg-3">
            <blockquote class="position-relative py-9 mb-7 mb-md-4 fs-4 text-center text-primary-800">
              <img class="d-md-none position-absolute start-50 top-0 translate-middle-x" src="@/assets/images/quote-left.png" alt="quote-left">
              <img class="d-none d-md-block position-absolute start-0 top-0" src="@/assets/images/quote-left.png" alt="quote-left">
              <p class="mt-3 mt-md-0 mb-3">讓使用者在觀賞與使用的旅程中，發現<mark class="mark p-0">設計的價值</mark></p>
              <p>
              而我在設計與開發的過程中，看見<mark class="mark p-0">自己的價值</mark></p>
              <img class="d-none d-md-block position-absolute end-0 bottom-0" src="@/assets/images/quote-right.png" alt="quote-right">
            </blockquote>
          </div>
        </div>
        <div class="row row-gap-4 justify-content-center pb-7">
          <div class="col-10 col-md-4 col-lg-3">
            <div class="text-center">
              <h6
                class="border-half position-relative d-inline-block pb-1 mb-2 lh-base fw-normal text-primary-600"
              >2B經驗</h6>
              <p class="text-primary-700">內部監控系統、庫存系統、採購系統、行銷整合系統</p>
            </div>
          </div>
          <div class="col-10 col-md-4 col-lg-3">
            <div class="text-center">
              <h6
                class="border-half position-relative d-inline-block pb-1 mb-2 lh-base fw-normal text-primary-600"
              >2C經驗</h6>
              <p class="text-primary-700">跨國美妝保養電商、個人品牌網站、醫美網站、電子商務</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container py-7 py-md-9 mt-7 mt-md-9">
      <ul class="row row-gap-9 mb-8 mb-md-9 list-unstyled">
        <li
          v-for="collection in collections"
          :key="collection.id"
          class="col-12 col-md-6"
        >
          <div class="card border-0">
            <button
              data-bs-toggle="modal"
              data-bs-target="#collectionModal"
              class="bg-transparent border-0"
              type="button"
            >
              <img
                :src="importImage(collection.id)"
                class="card-img-top rounded-4"
                :alt="`work${collection.id}`"
              >
            </button>
            <div class="card-body">
              <h3 class="card-title text-primary-700">{{ collection.name }}</h3>
              <p class="card-text mb-3 mb-md-4 text-primary-500">{{ collection.description }}</p>
              <div class="d-flex gap-3">
                <span
                  v-for="(tag, index) in collection.tags"
                  :key="`${tag}${index}`"
                  class="badge fs-6 lh-base fw-normal text-primary-700 bg-primary-200 rounded-4"
                >
                  {{ tag }}
                </span>
              </div>
            </div>
          </div>
        </li>
      </ul>
      <nav class="mb-7 mb-md-9" aria-label="Page navigation">
        <ul class="pagination justify-content-center gap-3">
          <li class="page-item">
            <a class="page-link text-primary-50 bg-primary-800 rounded-1 border-0" href="#">1</a>
          </li>
          <li class="page-item">
            <a class="page-link text-primary-700 rounded-1 border-0" href="#">2</a>
          </li>
          <li class="page-item">
            <a class="page-link text-primary-700 rounded-1 border-0" href="#">3</a>
          </li>
        </ul>
      </nav>
    </div>

    <div class="modal" id="collectionModal" tabindex="-1" aria-labelledby="modal" aria-hidden="true">
      <div
        class="modal-dialog modal-dialog-centered"
        style="--bs-modal-width: 1076px;"
      >
        <div class="modal-content rounded-4">
          <div class="modal-header pt-6 pb-0 px-6 px-md-7 mb-4 mb-md-7 border-0">
            <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
          </div>
          <div class="px-6 px-md-9">
            <h3 class="modal-title mb-2 text-primary-700 text-center">星際旅行訂票平台</h3>
            <p class="mb-4 mb-md-7 text-primary-500 text-center">悠遊宇宙的夢想，從這裡開始實現</p>
            <div class="row row-gap-4 justify-content-center justify-content-md-between align-items-center mb-4 mb-md-7">
              <div class="col-12 col-md-5 col-lg-7 text-primary-800">
                <p class="mb-0">STAR TRAVEL 為 KK 公司宇宙旅行的購票網站。</p>
                <p class="mb-0">主要從地球出發，目的地包含月球、火星、水星、木星；未來太空轉運站建置完畢，將再擴增目的地土星和金星。</p>
              </div>
              <div class="divider col-12 col-md-5 w-auto text-center text-md-start ps-md-4 pt-4 pt-md-0 text-primary-600">
                <p class="d-md-none mb-1">設計原則</p>
                <p class="d-md-none mb-3">宇宙旅行、深色背景、強烈視覺效果</p>
                <p class="d-md-none mb-1">開發方式</p>
                <p class="d-md-none mb-0">Bootstrap、Javascript、RWD</p>
                <p class="d-none d-md-block mb-1">設計原則：宇宙旅行、深色背景、強烈視覺效果</p>
                <p class="d-none d-md-block mb-0">開發方式：Bootstrap、Javascript、RWD</p>
              </div>
            </div>
          </div>
          <div class="modal-body py-7 text-center bg-primary-100">
            <img class="img-fluid mt-0 mt-md-7 mb-3 mb-md-4 rounded-4" src="@/assets/images/modal-image1.png" alt="modal-image1">
            <h4 class="mb-2 mb-md-3 fs-5 text-primary-800">主視覺</h4>
            <p class="mb-9 text-primary-600">可直接設定日期、起迄星球、張數，快速查詢可購買的票券。</p>
            <img class="img-fluid mb-3 mb-md-4 rounded-4" src="@/assets/images/modal-image2.png" alt="modal-image2">
            <h4 class="mb-2 mb-md-3 fs-5 text-primary-800">推薦查詢</h4>
            <p class="mb-md-7 text-primary-600">給予最快起飛，以及最熱門的景點推薦，協助使用者進行選擇。</p>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>