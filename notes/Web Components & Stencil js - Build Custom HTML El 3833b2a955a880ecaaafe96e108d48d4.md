# Web Components & Stencil.js - Build Custom HTML Elements

Senza framework come Angular, librerie come React o una conoscenza avanzata di JavaScript in generale. Solo con una funzionalità JavaScript nativa e "magica" chiamata "Web Components" (o "elementi HTML personalizzati"). I Web Components sono una combinazione di varie specifiche integrate nel browser. Iniziare a utilizzare queste funzionalità è semplicissimo e in poco tempo sarai in grado di creare i tuoi elementi HTML personalizzati, potenti e riutilizzabili (anche tra progetti diversi!).
Tali elementi personalizzati non sostituiscono Angular, React o Vue — al contrario, possono essere facilmente utilizzati in QUALSIASI progetto web, inclusi i progetti che già utilizzano questi framework e librerie.
In questo corso imparerai tutto questo da zero.
Ma non ci fermeremo qui. Sebbene iniziare sia abbastanza semplice, la creazione di componenti più complessi risulterà più impegnativa. Stencil.js è uno strumento che semplifica notevolmente la creazione di questi web component nativi grazie a funzionalità moderne come TypeScript e JSX (non li conosci? Nessun problema, li imparerai durante il corso!).
Nel dettaglio, in questo corso imparerai:

- come costruire elementi HTML personalizzati leggeri e riutilizzabili con le funzionalità native del browser
- come costruire web component di qualsiasi complessità — da un semplice tooltip fino a modali o drawer laterali
- come passare dati nei tuoi web component e utilizzarli al loro interno
- come emettere eventi personalizzati a cui puoi rispondere in JavaScript
- come usare lo Shadow DOM per circoscrivere gli stili CSS ai tuoi elementi personalizzati
- come usare Stencil.js per ottenere un flusso di sviluppo molto più semplice
- come sfruttare le numerose funzionalità di Stencil.js per creare web component nativi in modo molto più efficiente
- come distribuire/riutilizzare i tuoi web component in QUALSIASI progetto che utilizzi QUALSIASI framework JavaScript come Angular, React o Vue (o nessuno!)

Prerequisiti:

- Una conoscenza di base di JavaScript è indispensabile
- La conoscenza di ES6 JavaScript (const, let, classi, ...) è fortemente consigliata ma non strettamente necessaria — è incluso un breve ripasso nel corso
- NON è richiesta alcuna conoscenza di framework JavaScript (es. Angular, React, Vue)
- NON è richiesta alcuna conoscenza di TypeScript o JSX

Immergiamoci insieme in questa entusiasmante tecnologia!
A chi è rivolto questo corso:

- A chiunque sia interessato a creare tag HTML personalizzati!
- Agli studenti che vogliono approfondire una tecnologia web a prova di futuro, utilizzabile in qualsiasi applicazione web

![Screenshot 2026-06-18 alle 16.22.48.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_16.22.48.png)

![Screenshot 2026-06-18 alle 16.24.09.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_16.24.09.png)

![Screenshot 2026-06-18 alle 16.25.17.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_16.25.17.png)

![Screenshot 2026-06-18 alle 16.49.43.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_16.49.43.png)

commit [**00 Quick Demo of a Web Component**](https://github.com/simotae14/web-components/commit/e260d8498637bf3f1a28eaa8218909cf488a5708)

![Screenshot 2026-06-18 alle 16.55.12.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_16.55.12.png)

![Screenshot 2026-06-18 alle 17.34.34.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_17.34.34.png)

![Screenshot 2026-06-18 alle 17.37.53.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_17.37.53.png)

![Screenshot 2026-06-18 alle 17.38.14.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_17.38.14.png)

![Screenshot 2026-06-18 alle 17.41.05.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_17.41.05.png)

![Screenshot 2026-06-18 alle 17.47.31.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_17.47.31.png)

![Screenshot 2026-06-18 alle 18.01.30.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.01.30.png)

![Screenshot 2026-06-18 alle 18.03.52.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.03.52.png)

![Screenshot 2026-06-18 alle 18.05.54.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.05.54.png)

![Screenshot 2026-06-18 alle 18.07.16.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.07.16.png)

![Screenshot 2026-06-18 alle 18.08.49.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.08.49.png)

![Screenshot 2026-06-18 alle 18.09.04.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.09.04.png)

![Screenshot 2026-06-18 alle 18.11.04.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.11.04.png)

![Screenshot 2026-06-18 alle 18.12.25.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.12.25.png)

![Screenshot 2026-06-18 alle 18.14.29.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.14.29.png)

![Screenshot 2026-06-18 alle 18.15.47.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.15.47.png)

![Screenshot 2026-06-18 alle 18.16.55.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.16.55.png)

![Screenshot 2026-06-18 alle 18.18.44.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.18.44.png)

![Screenshot 2026-06-18 alle 18.21.11.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.21.11.png)

![Screenshot 2026-06-18 alle 18.22.50.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.22.50.png)

![Screenshot 2026-06-18 alle 18.27.38.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.27.38.png)

https://www.webcomponents.org/

![Screenshot 2026-06-18 alle 18.33.29.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-18_alle_18.33.29.png)

commit [**001 Creating My First Custom Element**](https://github.com/simotae14/web-components/commit/77af8e4ad3a518ca7cbbef906173a5a27ccf2d66)

posso accedere all’elemento html creato col this

![Screenshot 2026-06-19 alle 08.59.20.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-19_alle_08.59.20.png)

commit [**002 Using connectedCallback for DOM access**](https://github.com/simotae14/web-components/commit/370ab6b0a2fa21e9d5d356e94388444b85058854)

![Screenshot 2026-06-19 alle 16.16.50.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-19_alle_16.16.50.png)

commit [**003 Listening events inside the component**](https://github.com/simotae14/web-components/commit/d94815edbe95f99973a393e904bacbc840ccdbbd)

![Screenshot 2026-06-20 at 12.42.32.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_at_12.42.32.png)

Uso attributi nei custom elements ⇒ commit [**004 Using Attributes on Custom Elements**](https://github.com/simotae14/web-components/commit/44ef98f75478813939db3b60862101826cdde3b5)

Styling our elements ⇒ commit [**005 Styling our custom elements**](https://github.com/simotae14/web-components/commit/64cf9f407f4c43cd8c6db84fc8b16347c426fa37)

Shadow DOM ⇒ [**006 using the Shadow DOM**](https://github.com/simotae14/web-components/commit/206079b9fda4a8422670a9ac89dcb1e0b0b6e5a7)

![Screenshot 2026-06-20 alle 18.20.19.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_alle_18.20.19.png)

ora parte del codice sarà nascosto perchè parte dello shadow dom

![Screenshot 2026-06-20 alle 18.31.27.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_alle_18.31.27.png)

![Screenshot 2026-06-20 alle 18.31.58.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_alle_18.31.58.png)

per mostrare anche il testo dentro allo shadow dom dobbiamo usare i template

commit [**007 templates directly inside the html**](https://github.com/simotae14/web-components/commit/c218aa55836591394d4b4bbf3318339101900270)

Uso degli slots commit [**008 Using Slots**](https://github.com/simotae14/web-components/commit/9f767024823dead94025516adb663b6b773252d1)

Define the template inside the javascript commit [**009 Defining the Template in JavaScript**](https://github.com/simotae14/web-components/commit/08478c26281462b854bd22b3e0d19654715202bd)

commit [**010 using Style Tags in the Shadow DOM**](https://github.com/simotae14/web-components/commit/b68da7a75deb5fb526a751b10390a249c095288b)

commit [**011 Extending Built-In Elements**](https://github.com/simotae14/web-components/commit/e91527fe48d61286477f032cdd27c3e066c5f589)

## Diving Deeped into Web Components

![Screenshot 2026-06-20 alle 19.34.16.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_alle_19.34.16.png)

commit [**012 Styling slot Content Outside of the Shadow DOM**](https://github.com/simotae14/web-components/commit/629d018d909e4425af73bf2a7d6a074b2be2c309)

per scrivere stile di uno slot usare la css rule

```jsx
::slotted(.highlight) {
  style
}
```

se vuoi referenziare tutti i contenuti slotted usare

```jsx
::slotted(*) {
  stile
}
```

![Screenshot 2026-06-20 alle 22.51.04.png](Web%20Components%20&%20Stencil%20js%20-%20Build%20Custom%20HTML%20El/Screenshot_2026-06-20_alle_22.51.04.png)

commit [**013 Styling slot Content inside the Shadow DOM**](https://github.com/simotae14/web-components/commit/5f37f4edd80b6442a9ab27e1d4095a032e51e9f8)

dare stile al nostro custom element, al suo root component

dentro al component possiamo usare il selettore `:host`

commit  [**014 Styling the Host Component**](https://github.com/simotae14/web-components/commit/4749da89fcb07d25f20f5781de8029fec6ee7770)

**Conditional Host Styling**\

commit [**015 Conditional Host Styling**](https://github.com/simotae14/web-components/commit/33b7c7810fd50bb70ecc15e5bf6b32fa435e123b)

**Styling with the Host Content in mind**

possiamo usare `:host-context()` e tra parentesi mettere riferimento agli elementi all esterno del custom element

commit [**016 Styling with the Host Content in Mind**](https://github.com/simotae14/web-components/commit/d89d955f5a9d23a424e8566e26fb7792ba3ca1fe)

**Smart Dynamic Styling with CSS Variables**

commit [**017 Smart Dynamic Styling with CSS Variables**](https://github.com/simotae14/web-components/commit/d7043c4ff8988c8199403ce9aa3e748cd6a0e8de)

**Cleaning Up our Overall Styling

commit [**019 Cleaning Up our Overall Styling**](https://github.com/simotae14/web-components/commit/835765cae90644d20c57d9122a43e69947dbc47e)

**Observing attributes Changes

attributeChangeCallback

commit [**020 Observing attributes Changes**](https://github.com/simotae14/web-components/commit/f478f79fac985bb562ea1af53830148a480ff0fa)

**Adjusting the Component Behaviour Upon Attribute Changes

commit [**021 Adjusting the Component Behaviour Upon Attribute Changes**](https://github.com/simotae14/web-components/commit/06cb3067eae246798c98d4a599b20597f252ba70)

**Using disconnectedCallback

commit [**022 Using disconnectedCallback**](https://github.com/simotae14/web-components/commit/d2596c4d0d04179879fa1de15bb29203c8f9257a)

**Adding a render method

commit [**023 Adding a render method**](https://github.com/simotae14/web-components/commit/33d8b13c09904669dc0b173641bc07cd47723ba9)

**024 move the position relative to the :host css rule

commit [**024 move the position relative to the :host css rule](https://github.com/simotae14/web-components/commit/74caad1853dec531ad8b30a8a0a815a85afaf8d7)

Attached you find the module code, below are useful further resources:

More about Templates & Slots: 
[https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)

Google Article on Custom Elements: 
[https://developers.google.com/web/fundamentals/web-components/customelements](https://developers.google.com/web/fundamentals/web-components/customelements)

Google Article on Shadow DOM: 
[https://developers.google.com/web/fundamentals/web-components/shadowdom](https://developers.google.com/web/fundamentals/web-components/shadowdom)

*Building more complex components
** Unlocking the missing pieces

** Creating the Basics Modal Component

commit [**025 Creating the Basics Modal Component](https://github.com/simotae14/web-components/commit/7e80452d9b2d6c33d7351d5bb5912536dd7a18ab)

** Adding the Modal Container

commit [**026 Adding the Modal Container](https://github.com/simotae14/web-components/commit/149d73150fc6b55d76751b7c41c83dab7238b854)

** Styling the Modal Elements

commit [**027 Styling the Modal Elements](https://github.com/simotae14/web-components/commit/d3944fb74d87441acaf5f7af55b3c6db5a442a0b)

** Adding Some General App Logic

commit [**028 Adding Some General App Logic](https://github.com/simotae14/web-components/commit/03ef1f818ec635de67b573cd5fbec988b19f6512)

** Opening the Modal via CSS

commit [**029 Opening the Modal via CSS](https://github.com/simotae14/web-components/commit/43da7dfab025277825595af3907ecacadc6eb717)

** Public Methods & Properties

commit [**030 Public Methods & Properties](https://github.com/simotae14/web-components/commit/2006610773d136d032917151adcc178773876da4)

** slotchange & Getting Access to Slot Content

Using the slotchange event as event listener in a slot element, triggered everytime the content inside the slot changes

commit [**032 slotchange & Getting Access to Slot Content](https://github.com/simotae14/web-components/commit/e8abf23a59fb4165c3b96d9bb93bf1e401a2e1c5)

** Closing the Modal with Modal Buttons

commit [**033 Closing the Modal with Modal Buttons](https://github.com/simotae14/web-components/commit/5fb5703b58f6deadc9b0540f7e3fadd22468294a)

** Dispatching Custom Events

commit [**034 Dispatching Custom Events](https://github.com/simotae14/web-components/commit/68d417a06a6f17b2634584d04a139aef241cc7a4)

** Configuring Custom Events

Bubble up the cancel and confirm events

commit [**035 Configuring Custom Events](https://github.com/simotae14/web-components/commit/7f125bedc69dada623c0445dc9ff97b36f860638)

** Adding Enhancements & Modal Animations

Add the hide event to the click outside the modal on the backdrop

[More on Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Transitions/Using)

commit [**036 Adding Enhancements & Modal Animations](https://github.com/simotae14/web-components/commit/1f104ccc51de11cd9f8cd2e8842e4c3435a4b53f)

# Stencil (Intro)

[Browser support](https://www.webcomponents.org/)

To create a new stencil project just run

```jsx
npm init stencil
```

Choose component, to create a project for building web components.

** Creating a Stencil Project

commit [**037 Creating a Stencil Project](https://github.com/simotae14/web-components/commit/d8a96136a945f55c4736f5db8ab4ad9089a1437f)

** What is Stencil

It is A Compiler for Native Web Components

In the End it ships => Native JavaScript Web Components

The Stencil components are written in JS and TS and the Stencil Compiler compile them into Native JavaScript Web Components

Stencil.js spits out native, vanilla-JS web components.

BUT: These components have (vanilla) JavaScript added to them that enhances the web component experience by:

 - Loading component code lazily (i.e. source code gets only pulled into the page if it's really needed => This reduces the overall bundle size)

 - Loading required polyfills automatically for browsers that need it

 - Re-rendering the web (component) DOM efficiently (i.e. the DOM gets updated with as minimal impact as possible, to reduce the amount of work JS and the browser have to do)

** Diving Into a First Stencil Component

To turn a Stencil component into a Web Component it is enough to launch

```jsx
npm run build
```

# Stencil Diving Into the Basics

## Using the Development Server

To run the project just run

```jsx
npm start
```

to run the development server which is a web server. The build process happens in Browser's memory

It opens a new window in the browser at localhost:3333

commit [**038 Using the Development Server and remove generated component](https://github.com/simotae14/web-components/commit/7a497e05951ead6272d6dee2d6a0cc96c26db70c)

## Creating a New Stencil Web Component

Important: When creating new Stencil component files (which we'll do throughout this course), there is one extra import you should add at the top of your file:

```jsx
import { h } from '@stencil/core';
```

commit [**039 Creating a New Stencil Web Component](https://github.com/simotae14/web-components/commit/fb3559a58375631a18608b2ff5b547d6123939ab)

** Styling Stencil Component

commit [**039 Styling Stencil Component](https://github.com/simotae14/web-components/commit/e09476b9403b85f6ddda7f2e8c453d92dcd2ee82)

** Using Props

commit [**040 Using Props](https://github.com/simotae14/web-components/commit/655d1affa0ef02b33f39270dc0a7575b8f70e546)

__MUST READ__

In the next lecture, we'll also write some code that reflects prop values to their respective attributes. The explanation given there still is correct but the syntax changed:

_Instead of_

```jsx
@Prop({ reflectToAttr: true }) ...
```

_use_

```jsx
@Prop({ reflect: true }) ...
```

That's it!

** Configuring Props with reflect

commit [**041 Configuring Props with reflect](https://github.com/simotae14/web-components/commit/d06beb468e72713ae639995663259fd2ba84911d)

** Using Slots & Styling

commit [**042 Using Slots & Styling](https://github.com/simotae14/web-components/commit/2f121a66fa6902b60d392a647b1f7bfb651cc30e)

** Rendering Conditional Content

commit [**043 Rendering Conditional Content](https://github.com/simotae14/web-components/commit/908e1946551d78ccacd0a154e18076d1a392df07)

** Using Attributes for Styling only

commit [**044 Using Attributes for Styling only](https://github.com/simotae14/web-components/commit/16a1122cab2334210e28c9943cf3df449d4b938f)

** Using Props in Combination with Attributes

commit [**045 Using Props in Combination with Attributes](https://github.com/simotae14/web-components/commit/8325f99686c69a6444170bedcf376c43295fb6b7)

** Understanding Mutable Props

commit [**046 Understanding Mutable Props](https://github.com/simotae14/web-components/commit/9783e754bb0d2b5baa73bfad89ff66f1ca756c0e)

** Preparing Tabs

commit [**047 Preparing Tabs](https://github.com/simotae14/web-components/commit/5c659bf95014b5be081be7db000b31e5406858e8)

** Adding More Event Listeners to track the active tab
 
commit [**048 Adding More Event Listeners to track the active tab](https://github.com/simotae14/web-components/commit/e24bed58c76945f802f611900b0a0ddaeafa4527)

** Using State

Needed to react to changes from inside the component
 
commit [**049 Using State](https://github.com/simotae14/web-components/commit/fe1d9605c2de1086214b52e62bfc4029461f64b5)

** Adding Methods to Components to call from outside the Component

commit [**050 Adding Methods to Components to call from outside the Component](https://github.com/simotae14/web-components/commit/eca2735a5f22c450eb52cb1677a029c0733685e3)

** Adding a Backdrop

commit [**051 Adding a Backdrop](https://github.com/simotae14/web-components/commit/599c4cbfea371a32fa17d050a7d8a49e73b1fe8b)

helpful further resources:

Official Stencil.js Docs: [https://stenciljs.com/docs/introduction](https://stenciljs.com/docs/introduction)

** Creating a new Component Stock Price

commit [**052 Creating a new Component Stock Price](b)