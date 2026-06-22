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

commit [**025 Creating the Basics Modal Component]()