# 2. Hafta

## React Nedir ?

- Kullanıcı Arayüzleri oluşturabileceğimiz bir JavaScript kütüphanesidir.

- Tek sayfa uygulamalar geliştirmek için kullanılmaktadır.

- Facebook tarafından geliştirilmiştir.

- Tekrar tekrar kullanabileceğimiz **componentler** oluşturmamıza imkan sağlar.

> React **Virtual DOM** kullanılır yani DOM ile direkt etkileşimde bulunmak yerine sanal bir DOM ağacı üzerinde yapılan değişikleri, farklılıkları yakalayıp tüm DOM'u güncellemek yerine yalnızca değişikliğin yapıldığı yeri günceller ve azami düzeyde performans artışı yakalanır.

## JSX Nedir ?

JSX JavaScript’in bir söz dizimi uzantısıdır. React kullanırken ise oluşturmak istediğimiz elementleri **JSX** kullanarak rahatça hazırlayabiliriz ve **Babel** yardımıyla bunu React'in anlayacağı şekle çevirebiliriz.

```js
const name = "Josh Perez";
const element = <h1>Hello, {name}</h1>;
```

Örnek olarak yukarıdaki kodda basitçe JSX'i nasıl kullandığımızı görebilirsiniz.

###

```js
const element = <h1 className="greeting">Hello, world!</h1>;
```

```js
const element = React.createElement(
  "h1",
  { className: "greeting" },
  "Hello, world!"
);
```
