# Connect Your Tribe - UI-Stack

Ontwerp en bouw verschillende states van de UI-Stack.

## Context

Deze leertaak hoort bij sprint 7 "Connect Your Tribe". Dit is een deeltaak die je individueel uitvoert.

In het college _S07W1 - UI-Stack_ wordt behandeld wat de UI-Stack is en hoe je states van de UI-Stack kan bouwen.



## Doel van deze opdracht

Leren hoe je verschillende states van de UI-Stack kan tonen in de interface.


## Werkwijze

Opdracht: Ontwerp en bouw verschillende states van de UI-Stack

<img width="1180" alt="image" src="https://user-images.githubusercontent.com/1391509/153552195-31522b36-62bc-4e98-bf27-b3c994353583.png">



Deze opdracht gaat over alle fases van de DLC [ontwerpen](#ontwerpen) en [bouwen](#bouwen).



### Ontwerpen

Voordat je begint met bouwen schets je eerst een Wireflow voor de interactie en een breakdown-schets voor de techniek.

Teken een Wireflow met alle states van de UI-Stack die je wil tonen. Schets een Empty state, Loading state en/of Error state(s).

Schets de breakdown waarin je de HTML, CSS en JS alvast bedenkt voor de states die je wil tonen.


<details>
<summary>Aanpak</summary>

1. Schets een Wireflow met alle mogelijke output (schermen en states) die een gebruiker te zien krijgt
2. Schrijf onder elk scherm en state wat een gebruiker doet en wat de interface moet laten zien
3. Maak dan een breakdown-schets van de techniek die je nodig hebt, geef aan welke HTML, CSS en JS je nodig hebt
4. Welk HTML heb je nodig? Waar komt de HTMl voor de Empty State? En de Loading state?
5. Welke CSS heb je nodig voor de vormgeving van de states?
6. Welke JS heb je nodig voor het laden van de data en het tonen van de states? Waar komt de code voor de loading state? Welke code heb je nodig voor Error states?
  




#### Materiaal ontwerpfase

- [Wireframing User Flow with Wireflows](https://balsamiq.com/learn/articles/wireflows/)
- [UI-Stack - How to fix a bad user interface](https://www.scotthurff.com/posts/why-your-user-interface-is-awkward-youre-ignoring-the-ui-stack/)

</details>

### Bouwen

In de bouwfase ga je de HTML, CSS en JS toepassen die je nodig hebt om Empty state, Loading state en/of Error state te tonen.

<details>
<summary>Aanpak</summary>

1. Maak de HTML, CSS en JS om met een Fetch externe data te laden
1. Maak de HTML en CSS voor de Empty state
2. Maak de HTML, CSS en JS voor de Loading state
3. Maak de HTML, CSS en JS voor de Error-state

#### Materiaal bouwfase

- [Fetch API](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)
- Hier staat een [tutorial](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) voor het laden van JSON data en het aanmaken van HTMl elementen.
- Bij het laden van externe data kan de server verschillende [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) doorgeven, die kun je gebruiken om feedback te tonen.
- [Error handling while using native fetch API in JavaScript](https://learnwithparam.com/blog/how-to-handle-fetch-errors/)

</details>



## Criteria

Focus sprint 7 - De focus in deze sprint ligt op team building, samenwerken en hoe je een dynamische website kan maken waar bezoekers ook iets achter kunnen laten.	Het doel van deze sprint is binding tussen studenten creeeren. Met deze squad ga je het doen! Samen studeren, leren en elkaar helpen. En iets gezamenlijks maken met een database dingen. Een sneak peak naar de rest van het semester.

Deze leertaak hoort bij het gedragscriterium:

M: Je combineert aangeboden principes en conventies op het gebied van frontend, interface design en vormgeving.

Deze opdracht is done als:

- [ ] Er is een Wireflow getekend waarin de verschillende states van de UI-Stack zijn uitgewerkt
- [ ] Er is een Breakdown-schets met de techniek die nodig is voor het tonen van de states
- [ ] De states van de UI-Stack worden opgevangen in Javascript en getoond als dat nodig is
- [ ] De wireflow en code is gedocumenteerd in de Readme van de leertaak

