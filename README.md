# Campagne Email : Accès Études Québec (Étudiants FR)

Ce dossier contient les fichiers nécessaires pour la campagne d'emailing destinée aux étudiants français souhaitant étudier au Québec.

## Contenu du dossier
- `email.html` : Version HTML premium compatible Outlook/Gmail/Apple Mail.
- `email.txt` : Version texte brut pour une meilleure délivrabilité.
- `subject-lines.txt` : 8 suggestions d'objets et préheaders.

## Personnalisation (Placeholders)
Avant l'envoi, assurez-vous de configurer les variables suivantes dans votre outil d'emailing :
- `{{first_name}}` : Prénom du destinataire (Fallback : "Salut !").
- `{{city}}` : Ville de l'étudiant.
- `{{program_length}}` : Durée du programme (ex: "1 à 3 ans").
- `{{schools_count}}` : Nombre d'écoles partenaires (Optionnel).
- `{{student_call_url}}` : URL de réservation d'appel.
- `{{apply_url}}` : URL de candidature.
- `{{guide_url}}` : URL du guide gratuit.
- `{{utm_source}}`, `{{utm_medium}}`, `{{utm_campaign}}` : Paramètres de suivi.
- `{{company_name}}` : Accès Études Québec.
- `{{sender_email}}`, `{{sender_phone}}`, `{{physical_address}}` : Coordonnées de l'expéditeur.
- `{{unsubscribe_url}}` : Lien de désinscription.

## Checklist Conformité (CASL / RGPD)
- [ ] L'identité de l'expéditeur est claire.
- [ ] L'adresse physique est incluse dans le footer.
- [ ] Le lien de désinscription est fonctionnel.
- [ ] La raison de réception de l'email est mentionnée.

## Checklist Tests & Délivrabilité
- [ ] **Test Outlook** : Vérifier que les boutons VML s'affichent correctement.
- [ ] **Test Mobile** : Vérifier que le texte est lisible sans zoomer (min 14px).
- [ ] **Dark Mode** : Vérifier la lisibilité sur fond sombre.
- [ ] **Ratio Texte/Image** : Maintenir un bon ratio pour éviter les filtres spam.
- [ ] **Images ALT** : Ajouter des textes alternatifs si vous ajoutez des images.
- [ ] **Mots Spam** : Éviter "GRATUIT", "URGENT", "100%" en majuscules.

## Conseils Stratégiques
- L'objectif principal est la prise de rendez-vous téléphonique (`{{student_call_url}}`).
- L'appel est présenté comme un diagnostic rapide de 10-15 min pour réduire la friction.
- L'angle "écoles partenaires" rassure sur le sérieux de l'accompagnement.
