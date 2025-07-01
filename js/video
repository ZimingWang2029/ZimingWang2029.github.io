const videoBtn = document.getElementById("videoBtn");
const videoModal = document.getElementById("videoModal");
const closeBtn = document.querySelector(".close");
const youtubeVideo = document.getElementById("youtubeVideo");

// 点击按钮打开弹窗
videoBtn.addEventListener("click", () => {
  videoModal.style.display = "flex";
  // 替换 YOUR_VIDEO_ID 为你的 YouTube 视频 ID
  youtubeVideo.src = "https://www.youtube.com/embed/YOUR_VIDEO_ID?autoplay=1";
});

// 点击关闭按钮关闭弹窗
closeBtn.addEventListener("click", () => {
  videoModal.style.display = "none";
  youtubeVideo.src = ""; // 停止播放
});

// 点击弹窗外部关闭
window.addEventListener("click", (e) => {
  if (e.target === videoModal) {
    videoModal.style.display = "none";
    youtubeVideo.src = "";
  }
});
