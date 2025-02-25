selenium menggunakan POM
1. buat file loginTest.js yang berisi tasecase login, inventoryTest.js yang berisi tasecase add to cart sampai berhasil checkout
2. buat folder pages yang berisi class - class loginPage.js, inventoryPage.js dan checkoutPage.js
3. buat folder fixtures yang berisi data data dengan nama testData.js
4. buat folder screenshots yang otomatis ketika di run bakal menyimpan screenshots 
   script dibuat di loginTest.js dan inventoryTest.js
5. runnya npx mocha test\inventoryTest.js -t 0
   npx mocha test\loginTest.js -t 0
   npm run test:parallel
   npx mocha test/*.js --parallel --jobs 3 --timeout 10000