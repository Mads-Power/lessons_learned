# lessons_learned
list of things and templates that i have found useful over the years when starting a new project




## When staring a new project checklist
- [ ] Sjekk om prosjektet har design tegninger allerede eller om det er mulig å få inn en UX/UI designer.

- [ ] Hva og hvilke ting må være globalt(state managment), tenk DSA: holde verdier ved at man navigerer frem og tilbake.

- [ ] Start tidelig med grid system for et fleksibelt GUI  som passer med flere skjerm størrelser. 
- [ ] Les tydelig kravspekk flere ganger, prøv å finn spørsmål.

- [ ] Tegn en basic arkitektur tegning tidlig i prossessen; om ikke for prosjektet så gjør det for deg selv. Dette vil gjøre at du får et større overblikk over hva som må gjøres både backend og frontend.
- [ ]   Hvor lang tid har du på deg til å gjøre det som skal gjøres, hvilke features er "must have" og hvilke er " nice to have "(henger litt sammen med 4).


## frontend exploits

check input fields for to see if it is possible to hack. 
```
1. <script>alert(1)</script>
2. [Gotcha](javascript:alert(1))
3. [Gotcha](javascript&#58this;alert(1&#41))
4. <img src onerror="alert(document.cookie)"> prevention: change innerHTML to innerText.

```
