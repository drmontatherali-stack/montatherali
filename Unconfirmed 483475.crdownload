// خدمة عامل بسيطة: تفعيل فوري فقط بدون تخزين مؤقت (البيانات تعتمد على Firebase المباشر)
self.addEventListener('install', (e) => {
  self.skipWaiting();
});

self.addEventListener('activate', (e) => {
  e.waitUntil(self.clients.claim());
});

self.addEventListener('fetch', () => {
  // لا يوجد تخزين مؤقت حالياً — كل الطلبات تمر مباشرة للشبكة
});
