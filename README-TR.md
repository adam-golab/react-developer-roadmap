# React Developer Roadmap

[README in Chinese](README-CN.md)

[README in Japanese](README-JA.md)

[README in Korean](README-KO.md)

[README in Portuguese (Brazil)](README-PTBR.md)

[README in Russian](README-RU.md)

[README in Spanish](README-ES.md)

[README in Türkçe](README-TR.md)

> 2019'da bir React Geliştirici olmanını yol haritası:

Aşağıda, React geliştiricisi olmak için öğrenmek isteyeceğiniz kütüphaneleri ve alabileceğiniz yolu gösteren bir tablo bulabilirsiniz. Bu çizelgeyi bana, "Bir React geliştiricisi olarak bundan sonra ne öğrenmeliyim?" Diye soran herkes için bir ipucu olarak hazırladım.

## Feragat
> Bu yol haritasının amacı, size bu manzara hakkında bir fikir vermektir. Kalça ve modaya uygun olanı seçmeye teşvik etmek yerine, daha sonra ne öğrenileceği konusunda kafanız karışırsa, yol haritası size rehberlik edecektir. Bir aracın bazı durumlarda neden diğerlerinden daha uygun olacağına dair bir anlayış geliştirmelisiniz ve kalçanın ve modaya uygun birinin her zaman iş için en uygun olduğu anlamına gelmediğini unutmayın.

## Yol Haritası

![Roadmap](./roadmap-tr.png)

## Resources

1. Basics
    1. HTML
        * Temel HTML öğren.
        * Egzersiz olarak bir kaç sayfa yap.
    2. CSS
        * Temel CSS öğren
        * Öncelikle sayfaları şekillendir.
        * Grid ve Flexbox kullarak bir sayfa oluştur.
    3. Temel JS
        * Sözdizimi'ni(syntax) tanıyın.
        * Temel DOM işlemlerini öğren.
        * JS için özgün teknikleri öğren(Hoisting, Event Bubbling, Prototyping)
        * Birkaç AJAX çağrıları yapın. 
        * Yeni özellikleri öğren (ECMA Script 6+)
        * Ek olarak JQuery Öğren
2. Genel Geliştirici Özellikleri
    1. Git öğren, GitHub’da birkaç depo(repo) oluşturun, kodunuzu başkalarıyla paylaşın.
    2. HTTP(S) protokollerini, istek(request) metodlarını öğren  (GET, POST, PUT, PATCH, DELETE, OPTIONS)
    3. Google'ı kullanmaktan korkmayın [Power Searching with Google](http://www.powersearchingwithgoogle.com/)
    4. Terminali tanıyın ve shell'i yapılandırın. (bash, zsh, fish)
    5. Algoritmalar ve veri yapıları hakkında birkaç kitap okuyun.
    6. Tasarım kalıpları hakkında birkaç kitap okuyun.
3.  [official website](https://reactjs.org/tutorial/tutorial.html) üzerinden React öğrenin veya bazı kursları tamamlayın [courses](https://egghead.io/courses/the-beginner-s-guide-to-react)
4. Kullanacağınız araçları tanıyın
    1. Paket yönetimi
        * [npm](https://www.npmjs.com/)
        * [yarn](https://yarnpkg.com/lang/en/)
        * [pnpm](https://pnpm.js.org/)
    2. Görev çalıştırıcı
        * [npm scripts](https://docs.npmjs.com/misc/scripts)
        * [gulp](https://gulpjs.com/)
    * [Webpack](https://webpack.js.org/)
    * [Rollup](https://rollupjs.org/guide/en)
    * [Parcel](https://parceljs.org/)
5. Şekillendirme
    1. CSS On Derleyicileri
        * [Sass/CSS](https://sass-lang.com/)
        * [PostCSS](https://postcss.org/)
        * [Less](http://lesscss.org/)
        * [Stylus](http://stylus-lang.com/)
    2. CSS Framework'leri
        * [Bootstrap](https://getbootstrap.com/)
        * [Materialize](https://materializecss.com/), [Material UI](https://material-ui.com/), [Material Design Lite](https://getmdl.io/)
        * [Bulma](https://bulma.io/)
        * [Semantic UI](https://semantic-ui.com/)
    3. CSS Mimarisi
        * [BEM](http://getbem.com/)
        * [CSS Modules](https://github.com/css-modules/css-modules)
        * [Atomic](https://acss.io/)
        * [OOCSS](https://github.com/stubbornella/oocss/wiki)
        * [SMACSS](https://smacss.com/)
        * [SUITCSS](https://suitcss.github.io/)
    4. JS içinde CSS
        * [Styled Components](https://www.styled-components.com/)
        * [Radium](https://formidable.com/open-source/radium/)
        * [Emotion](https://emotion.sh/)
        * [JSS](http://cssinjs.org/)
        * [Aphrodite](https://github.com/Khan/aphrodite)
6. State Yönetimi
    1. [Component State](https://reactjs.org/docs/faq-state.html)/[Context API](https://reactjs.org/docs/context.html)
    2. [Redux](https://redux.js.org/)
        1. Asenkron(async) Işlemler(Side Effects)
            * [Redux Thunk](https://github.com/reduxjs/redux-thunk)
            * [Redux Better Promise](https://github.com/Lukasz-pluszczewski/redux-better-promise)
            * [Redux Saga](https://redux-saga.js.org/)
            * [Redux Observable](https://redux-observable.js.org)
        2. Yardımcılar
            * [Rematch](https://rematch.gitbooks.io/rematch/)
            * [Reselect](https://github.com/reduxjs/reselect)
        3. Veri Kalıcılığı
            * [Redux Persist](https://github.com/rt2zz/redux-persist)
            * [Redux Phoenix](https://github.com/adam-golab/redux-phoenix)
        4. [Redux Form](https://redux-form.com)
    3. [MobX](https://mobx.js.org/)
7. Tür/Tip Kontrolü
    * [PropTypes](https://reactjs.org/docs/typechecking-with-proptypes.html)
    * [TypeScript](https://www.typescriptlang.org/)
    * [Flow](https://flow.org/en/)
8. Form Yardımcıları
    * [Redux Form](https://redux-form.com)
    * [Formik](https://github.com/jaredpalmer/formik)
    * [Formsy](https://github.com/formsy/formsy-react)
    * [Final Form](https://github.com/final-form/final-form)
9. Yönlendirme
    * [React-Router](https://reacttraining.com/react-router/)
    * [Router5](https://router5.js.org/)
    * [Redux-First Router](https://github.com/faceyspacey/redux-first-router)
    * [Reach Router](https://reach.tech/router/)
10. API İstemcileri(clients)
    1. REST
        * [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
        * [SuperAgent](https://visionmedia.github.io/superagent/)
        * [axios](https://github.com/axios/axios)
    2. GraphQL
        * [Apollo](https://www.apollographql.com/docs/react/)
        * [Relay](https://facebook.github.io/relay/)
        * [urql](https://github.com/FormidableLabs/urql)
11. Yardımcı Kütüphaneler
    * [Lodash](https://lodash.com/)
    * [Moment](https://momentjs.com/)
    * [classnames](https://github.com/JedWatson/classnames)
    * [Numeral](http://numeraljs.com/)
    * [RxJS](http://reactivex.io/)
    * [ImmutableJS](https://facebook.github.io/immutable-js/)
    * [Ramda](https://ramdajs.com/)
12. Test Yapma
    1. Birim Testi
        * [Jest](https://facebook.github.io/jest/)
        * [Enzyme](http://airbnb.io/enzyme/)
        * [Sinon](http://sinonjs.org/)
        * [Mocha](https://mochajs.org/)
        * [Chai](http://www.chaijs.com/)
        * [AVA](https://github.com/avajs/ava)
        * [Tape](https://github.com/substack/tape)
    2. Uçtan Uca Test
        * [Selenium](https://www.seleniumhq.org/), [Webdriver](http://webdriver.io/)
        * [Cypress](https://cypress.io/)
        * [Puppeteer](https://pptr.dev/)
        * [Cucumber.js](https://github.com/cucumber/cucumber-js)
        * [Nightwatch.js](http://nightwatchjs.org/)
    3. Entegresyon Testi
        * [Karma](https://karma-runner.github.io/)
13. Uluslararası Yapma //TODO:
    * [React Intl](https://github.com/yahoo/react-intl)
    * [React i18next](https://react.i18next.com/)
14. Sunucu Taraflı İşleme
    * [Next.js](https://nextjs.org/)
    * [After.js](https://github.com/jaredpalmer/after.js)
    * [Rogue](https://github.com/alidcastano/rogue.js)
15. Statik Site Üretici
    * [Gatsby](https://www.gatsbyjs.org/)
16. Arka Uç(Backend) Framework Entegrasyonu
    * [React on Rails](https://shakacode.gitbooks.io/react-on-rails/content/)
17. Mobil
    * [React Native](https://facebook.github.io/react-native/)
    * [Cordova](https://cordova.apache.org/)/[Phonegap](https://phonegap.com/)
18. Masaüstü
    * [Proton Native](https://proton-native.js.org/)
    * [Electron](https://electronjs.org/)
    * [React Native Windows](https://github.com/Microsoft/react-native-windows)
19. Sanal Gerçeklik
    * [React 360](https://facebook.github.io/react-360/)

## Son Olarak

Yol haritasının iyileştirilebileceğini düşünüyorsanız, lütfen güncellemeleri olan bir PR açın ve sorunları gönderin. Ayrıca, bunu geliştirmeye devam edeceğim, bu nedenle bu depoyu tekrar ziyaret etmek için yıldız vermek isteyebilirsiniz.

## Katkı Sunma

Yol haritası [Draw.io] (https://www.draw.io/) kullanılarak oluşturulmuştur. Proje dosyası `/ src` dizininde bulunabilir. Değiştirmek için draw.io dosyasını açın, ** Mevcut Diyagramı Açın ** üzerine tıklayın ve project ile `xml` dosyasını seçin. Yol haritasını sizin için açacak. Güncelleyin, beni oku içindeki görüntüleri yükleyin ve güncelleyin ve bir PR oluşturun (png olarak dışa aktar).

- İyileştirmelerle bir Pull Request açın
- Issues'da ki fikirleri tartışın
- Kelimeyi yaygınlaştırın.

## Lisans

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
