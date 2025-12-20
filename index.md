---
layout: default
title: Beranda
permalink: /
---

<style>
  .hero {
    text-align: center;
    padding: 30px 0 40px;
    background: linear-gradient(135deg, #f5f9ff 0%, #e3f2fd 100%);
    border-radius: 12px;
    margin-bottom: 32px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.06);
  }
  .hero h1 {
    font-size: 2.2rem;
    color: #0d47a1;
    margin-bottom: 16px;
    opacity: 0;
    animation: fadeIn 1.2s forwards;
  }
  .hero p {
    font-size: 1.1rem;
    max-width: 700px;
    margin: 0 auto 24px;
    line-height: 1.6;
    opacity: 0;
    animation: fadeIn 1.2s 0.3s forwards;
  }
  .hero-img {
    width: 100%;
    max-width: 500px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.12);
    opacity: 0;
    animation: fadeInUp 1s 0.6s forwards;
  }
  @keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
  }
  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(20px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  @media (max-width: 600px) {
    .hero h1 { font-size: 1.7rem; }
    .hero p { font-size: 1rem; }
    .hero-img { max-width: 90%; }
  }
</style>

<div class="hero">
  <h1>🎯 Portal Akreditasi Prodi Broadband Multimedia 2026</h1>
  
  <p>
    **Target Asesmen**: **September 2026**<br>
    **Status Saat Ini**: Persiapan Tahap Awal (Desember 2025)
  </p>
  
  <img 
    src="https://cdn-icons-png.flaticon.com/512/4238/4238318.png" 
    alt="Akreditasi LAM Teknik"
    class="hero-img"
  >
  
  <p style="margin-top: 20px; animation: fadeIn 1.2s 0.9s forwards; opacity: 0;">
    Website ini merupakan dokumen pendukung yang disusun sesuai **Standar Akreditasi LAM Teknik**.<br>
    Gunakan menu di atas untuk mengakses dokumen per standar atau lihat progres keseluruhan.
  </p>
</div>
