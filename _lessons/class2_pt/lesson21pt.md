---
layout: lesson
class: "2"
lesson: "21"
lang: pt
---


# Lesson 2.21: Sickness 

[comment]: <> NOTE: all the words go in there: https://docs.google.com/spreadsheets/d/1eR2dAVnsdWWox6CqvY4HZwZd3VhYF9IME_EfQQAfXTs/edit#gid=0

{% include player2.html identifier="vocabulary" class=page.class lesson=page.lesson %}
## Vocabulary 


### Sickness 

{% include wordgrid.html 
		class=page.class 
		lesson=page.lesson
		lang=page.lang 
		section="sickness"
		voiceover="vocabulary"
		database=site.data.vocabulary 
		trial=site.trialdeploy %}


### Advice 

{% include wordgrid.html 
		class=page.class 
		lesson=page.lesson 
		lang=page.lang
		section="advice"
		voiceover="vocabulary"
		database=site.data.vocabulary 
		trial=site.trialdeploy %}




{% include player2.html identifier="conversation" class=page.class lesson=page.lesson %}

## Conversation

> Person 1: **Hi, I’m not feeling too well.**   
> Person 2: **Yes, you look tired. What’s the matter?**    
> P1: **I have a sore throat.**   
> P2: **Do you have a cough?**  
> P1: **No, I don’t.**  
> P2: **Do u have an earache?**  
> P1: **Kind of, my right ear hurts a little and I have a runny nose and a bad headache.**  
> P2: **That’s too bad. Have you seen a doctor?**    
> P1: **No. I’m fine, really. I think I just have a cold.**    
> P2: **You have a fever. Take some vitamin C and drink lots of water! Relax, don’t work too hard or you are gonna get worse. Why don’t you go home and have a rest now?**  
> P1: **Good idea. Can you take notes for me in class?**  
> P2: **Sure. I hope you feel better soon.**  
> P1: **Thanks.**  


{% include player2.html identifier="explanation" class=page.class lesson=page.lesson %}

## Explanation
### 1. I have a runny nose and a bad headache.
Eu tenho uma coriza e uma dor de cabeça ruim.
- **I have a massive headache and my stomach hurts.** *Eu tenho uma enorme dor de cabeça e meu estômago dói.*
- **My right ear hurts and I feel a sharp pain in it every time I yawn.** *Minha orelha direita dói e sinto uma dor aguda nela toda vez que bocejo.*
- **I have a cold so bad, I threw up at least 6 times today.**  *Tenho um resfriado tão ruim que vomitei pelo menos 6 vezes hoje.*


{% if site.trialdeploy %}
  {% include list_placeholder.html start=3 stop=6 %}
  {% else %}
  

### 2. That's too bad. Have you seen a doctor?
Isso é ruim. Você já viu um médico?
- **I'm so sorry to hear that. Have you been to a doctor?** *Eu sinto muito por ouvir isso. Você foi a um médico?*
- **That is horrible! Call the ambulance ASAP!** *Isso é horrível! Ligue para a ambulância o mais rápido possível!*
- **I can't believe she is sick. She probably ate something spoiled.** *Não acredito que ela ficou doente. Provavelmente comeu algo estragado.*

### 3. You have a fever. Take some vitamin C and drink lots of water!
Você tem febre. Pegue um pouco de vitamina C e beba muita água!
- **You have a headache? Take a headache pill and try to get some rest!** *Você tem dor de cabeça? Toma um comprimido de dor de cabeça e tenta descansar!*
- **Jane said she has a toothache. I told her to go to a dentist immediately.** *Jane disse que ela teve uma dor de dente. Eu disse a ela para ir a um dentista imediatamente.*
- **Her nosebleed won't stop. Take her to a doctor immediately!**  *Sua hemorragia nasal não vai parar. Leve-a imediatamente ao médico!*

### 4. I hope you feel better soon. 

Espero que te sintas melhor em breve.

- **I hope your headache subsides and you feel a lot better.** *Espero que sua dor de cabeça diminua e você se sente muito melhor.*
- **You'll feel better in no time. Trust me.** *Você se sentirá melhor em breve. Confie em mim.*
- **Don't worry, the nausea will wear off in an hour or two.** *Não se preocupe, a náusea desaparecerá em uma hora ou duas.*

### 5. Try not to eat anything oily or spicy for a few days!

Tente não comer nada oleoso ou picante por alguns dias!
- **Avoid working if you don't feel well!** *Evite trabalhar se você não se sentir bem.*
- **You shouldn't stop taking antibiotics just because you feel slight improvement.** *Você não deve parar de tomar antibióticos apenas porque sente uma leve melhoria.*
- **Try not to eat anything a day before your surgery!** *Tente não comer nada um dia antes da cirurgia!*
{% endif %}