# PRD — Application d’apprentissage de l’anglais assistée par IA

## 1. Vue d’ensemble

### Nom de travail
EnglishFlow AI

### Type de produit
Application web responsive, avec possibilité d’évolution vers mobile.

### Résumé en une phrase
EnglishFlow AI est une application d’apprentissage de l’anglais qui combine parcours pédagogique structuré, conversation texte, conversation vocale, simulation d’appel vidéo et révision intelligente pour aider un utilisateur à progresser pendant plusieurs semaines de manière guidée, engageante et personnalisée.

### Pourquoi ce produit existe
Les applications classiques sont souvent soit trop gamifiées et peu profondes, soit trop conversationnelles sans structure, soit trop scolaires. Le but est de créer une expérience complète qui mêle structure, pratique réelle, feedback, mémoire pédagogique et engagement long terme. [cite:1]

---

## 2. Problème

### Problème principal
Les apprenants de niveau débutant/intermédiaire faible ont du mal à progresser durablement parce qu’ils manquent de :
- structure claire sur plusieurs semaines ;
- feedback personnalisé ;
- pratique réelle de l’oral ;
- répétition intelligente ;
- contenu motivant et assez interactif pour tenir dans le temps. [cite:1]

### Problèmes secondaires
- Les apps type chat IA ne donnent pas toujours un vrai plan pédagogique.
- Les apps traditionnelles n’entraînent pas assez la conversation réelle.
- L’utilisateur ne sait pas toujours quoi faire chaque jour.
- La progression manque parfois de visibilité.
- Les erreurs récurrentes ne sont pas assez exploitées pour personnaliser les exercices. [page:1][page:2]

---

## 3. Vision produit

Créer un “coach d’anglais complet” capable d’accompagner l’utilisateur pendant 8 à 12 semaines minimum, avec :
- un programme guidé ;
- des leçons interactives ;
- de la pratique texte ;
- de la pratique orale ;
- une simulation de conversation vidéo ;
- un suivi de progression ;
- une mémoire des erreurs et mots appris. [page:1][page:2]

---

## 4. Objectifs produit

### Objectifs utilisateur
- Aider l’utilisateur à pratiquer l’anglais chaque jour en sessions courtes.
- Rendre l’apprentissage clair, motivant et durable.
- Développer la compréhension, l’expression écrite, l’expression orale, le vocabulaire et la confiance.

### Objectifs business / produit
- Lancer un MVP différenciant rapidement.
- Obtenir un bon taux de rétention sur 2 à 4 semaines.
- Valider que la combinaison “parcours + conversation + mémoire pédagogique” crée plus de valeur qu’un simple chatbot.

### Hypothèses à valider
- Les utilisateurs préfèrent un parcours structuré à une interface libre de type chat seul.
- Le mode voix augmente l’engagement.
- Le mode “appel vidéo” perçu comme immersif augmente la rétention.
- La personnalisation basée sur les erreurs améliore la progression ressentie. [page:1][page:2][web:38]

---

## 5. Public cible

### Persona principal
Jeune apprenant ou adulte débutant/intermédiaire faible qui veut progresser en anglais avec un outil moderne, guidé, pratique et moins ennuyeux qu’un cours classique.

### Niveau visé
A0 à B1 au lancement, avec concentration forte sur A1–A2 et début B1.

### Besoins
- Savoir quoi faire chaque jour ;
- parler plus facilement ;
- comprendre plus de phrases utiles ;
- voir des progrès ;
- apprendre sans se perdre dans une interface compliquée.

### Frustrations
- Trop de théorie ;
- pas assez de pratique réelle ;
- conversations IA trop floues ;
- contenu répétitif ;
- manque de motivation sur la durée. [cite:1]

---

## 6. Proposition de valeur

L’application combine 5 couches dans une seule expérience :
1. Parcours structuré sur plusieurs semaines
2. Micro-leçons interactives
3. Chat IA pour pratiquer par message
4. Conversation vocale
5. Appel vidéo simulé avec avatar/coach IA

La différenciation centrale est la mémoire pédagogique : l’application retient les erreurs, les mots appris, les thèmes déjà vus et adapte la suite du parcours. [page:1][page:2]

---

## 7. Périmètre MVP

### Inclus dans le MVP
- Authentification simple
- Onboarding avec test de niveau léger
- Dashboard de progression
- Parcours de 8 semaines
- Leçons quotidiennes
- Exercices interactifs
- Chat texte IA
- Mode conversation vocale
- Mode appel vidéo simulé
- Correction et feedback
- Système de révision espacée
- Historique d’apprentissage
- Profil utilisateur
- Admin simple pour gérer contenu et parcours

### Hors scope MVP
- Réseau social entre apprenants
- Marketplace de professeurs humains
- Cours live multi-utilisateurs
- Génération vidéo réaliste temps réel
- Support de 10 langues d’interface
- Certification officielle
- Gamification complexe type ligues mondiales
- Place de marché B2B écoles/entreprises. [web:32][web:35]

---

## 8. Fonctionnalités principales

### F1. Onboarding et diagnostic initial
L’utilisateur crée un compte, choisit ses objectifs, indique son niveau estimé, son temps quotidien et ses priorités.
Le système propose ensuite un parcours initial.

#### Critères d’acceptation
- L’utilisateur peut s’inscrire avec email et mot de passe.
- L’utilisateur répond à un mini questionnaire de niveau et d’objectifs.
- Le système assigne un niveau de départ et une première semaine de contenu.
- L’utilisateur voit immédiatement un plan clair “quoi faire aujourd’hui”.

### F2. Parcours pédagogique structuré
Le produit propose un plan découpé en semaines, modules et leçons.

#### Critères d’acceptation
- Chaque semaine a un thème, des objectifs et des activités.
- Chaque leçon dure 5 à 15 minutes.
- Le système affiche l’ordre recommandé.
- L’utilisateur peut reprendre là où il s’est arrêté.

### F3. Leçons interactives
Le produit contient des exercices variés :
- vocabulaire ;
- phrases à compléter ;
- reformulation ;
- compréhension courte ;
- mini dialogue ;
- écoute ;
- répétition.

#### Critères d’acceptation
- Chaque leçon comprend plusieurs interactions.
- Un feedback est donné après chaque réponse ou bloc de réponses.
- Les erreurs sont enregistrées pour la révision future.

### F4. Chat texte IA
L’utilisateur peut discuter avec un coach IA par message.

#### Critères d’acceptation
- L’utilisateur envoie des messages en anglais.
- L’IA répond de manière adaptée au niveau de l’utilisateur.
- L’utilisateur peut demander correction, traduction simple, explication et reformulation.
- Les erreurs importantes sont stockées.

### F5. Mode voix
L’utilisateur peut parler au coach IA et recevoir réponse audio + transcription.

#### Critères d’acceptation
- L’utilisateur peut démarrer une session orale.
- Sa voix est transcrite.
- L’IA répond en texte et audio.
- Une fiche de feedback est générée après la session.

### F6. Appel vidéo simulé
Le produit propose une interface type appel vidéo avec avatar ou personnage IA.

#### Critères d’acceptation
- L’écran reproduit une expérience immersive d’appel.
- Le personnage a un rôle ou un contexte précis.
- La conversation suit un scénario souple.
- L’utilisateur reçoit un bilan à la fin.

### F7. Mémoire pédagogique
Le système conserve :
- mots appris ;
- erreurs fréquentes ;
- points de grammaire fragiles ;
- thèmes déjà vus ;
- historique des sessions.

#### Critères d’acceptation
- Le profil pédagogique est mis à jour après chaque activité.
- Le système réutilise ces données pour recommander la suite.
- L’utilisateur peut voir certains éléments de sa progression.

### F8. Révision espacée
Le produit repropose automatiquement les notions mal maîtrisées.

#### Critères d’acceptation
- Les erreurs et mots fragiles alimentent une file de review.
- Le système planifie des rappels ou activités de révision.
- L’utilisateur voit une section “à revoir aujourd’hui”.

### F9. Dashboard et progression
L’utilisateur suit son avancée.

#### Critères d’acceptation
- Affichage du streak, du temps passé, des modules finis, des forces/faiblesses.
- Vue simple de la progression sur la semaine et sur le mois.
- Affichage des objectifs du jour.

### F10. Admin contenu
Un administrateur peut gérer les modules, les leçons et certaines consignes.

#### Critères d’acceptation
- Création / modification / archivage de modules.
- Organisation par niveau, thème et semaine.
- Prévisualisation simple des contenus.

---

## 9. User stories

### Côté apprenant
- En tant qu’apprenant, je veux connaître mon niveau de départ pour suivre un parcours adapté.
- En tant qu’apprenant, je veux savoir quoi faire aujourd’hui pour ne pas perdre de temps.
- En tant qu’apprenant, je veux parler en anglais avec l’application pour gagner en fluidité.
- En tant qu’apprenant, je veux recevoir des corrections compréhensibles pour m’améliorer.
- En tant qu’apprenant, je veux revoir ce que j’ai mal compris pour mieux retenir.
- En tant qu’apprenant, je veux voir mes progrès pour rester motivé.
- En tant qu’apprenant, je veux faire des conversations réalistes par message, voix ou appel simulé.
- En tant qu’apprenant, je veux des sessions courtes pour pouvoir pratiquer tous les jours.

### Côté admin
- En tant qu’admin, je veux créer des modules et leçons sans modifier le code.
- En tant qu’admin, je veux classer les contenus par niveau et thème.
- En tant qu’admin, je veux ajuster les prompts et scénarios d’IA.

---

## 10. Flux utilisateurs

### Flux 1 — Première utilisation
1. L’utilisateur crée son compte
2. Il passe un mini onboarding
3. Il reçoit son niveau estimé
4. Il découvre son dashboard
5. Il lance sa première leçon
6. Il termine par une mini conversation texte ou voix

### Flux 2 — Session quotidienne
1. L’utilisateur ouvre l’app
2. Il voit “quoi faire aujourd’hui”
3. Il fait une leçon
4. Il fait une révision
5. Il lance une conversation
6. Il reçoit un score/bilan

### Flux 3 — Appel vidéo simulé
1. L’utilisateur choisit un scénario
2. L’appel démarre
3. Le personnage IA pose des questions
4. L’utilisateur répond à l’oral
5. L’IA adapte la conversation
6. Fin de session avec feedback, vocabulaire, erreurs et conseils

---

## 11. Exigences non fonctionnelles

### Performance
- Temps de chargement initial raisonnable
- Réponse texte rapide
- Latence voix la plus basse possible pour rester naturelle

### UX
- Interface simple, mobile-first
- Le parcours du jour doit être compréhensible en moins de 10 secondes
- Les actions principales doivent être visibles immédiatement

### Fiabilité
- Historique des sessions conservé
- Reprise d’une session interrompue si possible

### Sécurité
- Authentification sécurisée
- Données utilisateurs protégées
- Journalisation minimale mais utile

### Scalabilité
- Architecture suffisamment modulaire pour ajouter d’autres langues plus tard

### IA / qualité
- Réponses adaptées au niveau de l’utilisateur
- Feedback cohérent
- Pas de contenu toxique ou hors sujet
- Détection des réponses trop complexes pour les simplifier. [web:33][web:36]

---

## 12. Architecture fonctionnelle attendue

### Front
- Application web responsive
- Dashboard
- Leçons
- Chat
- Voix
- Appel vidéo simulé
- Profil
- Admin

### Back
- Auth
- Gestion utilisateurs
- Gestion parcours / contenu
- Moteur de progression
- Mémoire pédagogique
- Historique sessions
- API conversation IA
- API scoring / feedback

### IA
- Génération de réponse texte
- Correction grammaticale
- Reformulation niveau cible
- Création de feedback
- Suggestions d’exercices
- Personnalisation selon mémoire utilisateur

---

## 13. Modèle de données initial

### Entités principales
- User
- UserProfile
- PlacementTestResult
- LearningGoal
- Course
- Module
- Lesson
- Exercise
- Session
- Message
- VoiceSession
- VideoScenario
- VocabularyItem
- UserVocabularyProgress
- GrammarWeakPoint
- ReviewQueue
- FeedbackReport
- Achievement

### Champs clés
#### User
- id
- email
- password_hash
- created_at

#### UserProfile
- user_id
- current_level
- target_level
- daily_goal_minutes
- learning_preferences
- strengths
- weaknesses

#### Module
- id
- level
- week_number
- title
- theme
- objective

#### Lesson
- id
- module_id
- type
- estimated_duration
- order_index

#### Session
- id
- user_id
- session_type
- started_at
- ended_at
- score
- summary

#### ReviewQueue
- id
- user_id
- item_type
- item_id
- priority
- due_at

---

## 14. Priorisation

### Must have
- Onboarding
- Parcours structuré
- Leçons interactives
- Chat texte
- Mémoire pédagogique basique
- Révision espacée
- Dashboard simple

### Should have
- Mode voix
- Feedback détaillé post-session
- Admin contenu

### Could have
- Appel vidéo simulé avancé
- Badges / streaks avancés
- Personnalité de coachs multiples

### Won’t have now
- Profs humains
- Communauté
- Vidéo générée ultra réaliste
- Version entreprise. [web:32]

---

## 15. Métriques de succès

### Produit
- Taux d’activation J1
- Taux de complétion onboarding
- Nombre moyen de sessions par semaine
- Rétention semaine 1 / semaine 2 / semaine 4
- Pourcentage d’utilisateurs qui utilisent le mode voix
- Pourcentage d’utilisateurs qui reviennent après un appel simulé

### Pédagogie
- Temps d’apprentissage moyen par semaine
- Taux de réussite aux exercices
- Évolution du nombre d’erreurs récurrentes
- Nombre de mots maîtrisés
- Progression perçue par l’utilisateur

### Qualité IA
- Taux de réponses jugées utiles
- Taux de correction jugée claire
- Temps moyen de réponse. [web:29][web:31][web:35]

---

## 16. Risques

- Scope trop large dès le départ
- Dépendance excessive à une IA externe
- Latence trop élevée en voix
- Contenu pédagogique insuffisant
- Coût par utilisateur trop élevé
- Expérience vidéo gadget si mal exécutée
- Feedback IA incohérent
- Complexité de personnalisation sur la durée. [page:1][page:2][web:38]

### Mitigation
- Commencer avec un MVP web
- Limiter les scénarios d’appel vidéo au départ
- Construire un moteur de contenu simple mais extensible
- Mesurer usage réel avant d’ajouter des features lourdes
- Prioriser la valeur pédagogique sur l’effet wow

---

## 17. Roadmap MVP

### Phase 1
- PRD finalisé
- wireframes
- modèle de données
- architecture technique
- base auth + dashboard

### Phase 2
- modules / leçons / exercices
- progression
- review queue
- admin contenu basique

### Phase 3
- chat texte IA
- mémoire pédagogique
- feedback automatique

### Phase 4
- voix
- transcription
- synthèse vocale
- rapport de session

### Phase 5
- appel vidéo simulé
- scénarios
- analytics

---

## 18. Décisions produit importantes

- Le produit est d’abord pensé mobile-first mais construit en web app.
- La structure pédagogique est plus importante que la simple conversation libre.
- Le mode vidéo est une immersion UX, pas une vraie promesse de vidéo générée réaliste.
- La personnalisation doit venir des données d’apprentissage, pas uniquement du prompt.

---

## 19. Demandes explicites au système de conception / développement

Le système qui utilise ce PRD doit :
- proposer une architecture technique cohérente ;
- découper le projet en tâches ;
- définir les écrans ;
- proposer la base de données ;
- écrire les user flows détaillés ;
- lister les APIs nécessaires ;
- générer une première version du code du MVP ;
- ne pas ajouter de fonctionnalités hors scope ;
- toujours respecter la priorité au MVP.
