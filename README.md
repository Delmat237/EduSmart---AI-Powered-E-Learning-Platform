# 🎓 EduSmart - Plateforme d'E-Learning Alimentée par l'IA

![Éducation](https://img.shields.io/badge/Education-E--Learning-brightgreen.svg)
![React](https://img.shields.io/badge/React-18.x-61DAFB.svg)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1.svg)

> **Plateforme d'apprentissage intelligente pour l'éducation africaine**

Une plateforme d'e-learning révolutionnaire qui exploite l'intelligence artificielle pour offrir des expériences éducatives personnalisées, conçue spécifiquement pour le paysage éducatif africain avec un support multilingue et des parcours d'apprentissage adaptatifs.

## 📋 Table des Matières
- [Fonctionnalités Clés](#-fonctionnalités-clés)
- [Architecture du Système](#-architecture-du-système)
- [Pile Technologique](#-pile-technologique)
- [Démarrage Rapide](#-démarrage-rapide)
- [Aperçu des Fonctionnalités](#-aperçu-des-fonctionnalités)
- [Fonctionnalités IA](#-fonctionnalités-ia)
- [Documentation API](#-documentation-api)
- [Système de Gamification](#-système-de-gamification)
- [Fonctionnalités de Sécurité](#-fonctionnalités-de-sécurité)
- [Localisation et Accessibilité](#-localisation-et-accessibilité)
- [Application Mobile](#-application-mobile)
- [Intégration Blockchain](#-intégration-blockchain)
- [Analyses et Rapports](#-analyses-et-rapports)
- [Stratégie de Tests](#-stratégie-de-tests)
- [Guide de Déploiement](#-guide-de-déploiement)
- [Contribution](#-contribution)
- [Licence](#-licence)
- [Remerciements](#-remerciements)
- [Auteur](#-auteur)

## 🌟 Fonctionnalités Clés

### **Moteur d'Apprentissage Adaptatif**
- **Parcours d'Apprentissage Personnalisés** - Adaptation du programme par IA
- **Recommandation de Contenu Intelligente** - Basée sur les schémas d'apprentissage
- **Analyse de Performance** - Suivi en temps réel des progrès
- **Analyse des Lacunes de Compétences** - Identification et correction des lacunes

### **Support Multilingue**
- **Intégration des Langues Locales** - Français, Anglais, langues africaines
- **Traduction Automatique** - Traduction de contenu en temps réel
- **Adaptation Culturelle** - Exemples pertinents contextuellement
- **Synthèse Vocale** - Accessibilité pour tous les apprenants

### **Gamification et Engagement**
- **Système de Récompenses** - Badges, niveaux et récompenses
- **Classements** - Compétition saine entre étudiants
- **Défis Interactifs** - Activités d'apprentissage engageantes
- **Visualisation des Progrès** - Parcours d'apprentissage visuel

### **Certification par Blockchain**
- **Certificats Vérifiés** - Certificats infalsifiables
- **Vérification des Compétences** - Certifications reconnues par les employeurs
- **Micro-crédits** - Reconnaissance granulaire des compétences
- **Portfolio Numérique** - Présentation complète des compétences

## 🏗️ Architecture du Système

```
┌────────────────────┐    ┌────────────────────┐    ┌────────────────────┐
│   Client React     │    │   Spring Boot      │    │   Moteur IA        │
│   (Frontend)       │◄──►│   (Backend)        │◄──►│   (TensorFlow)     │
└────────────────────┘    └────────────────────┘    └────────────────────┘
        │                        │                        │
        │                        │                        │
        ▼                        ▼                        ▼
┌────────────────────┐    ┌────────────────────┐    ┌────────────────────┐
│   Appli Mobile     │    │   Base MySQL       │    │   Moteur Contenu   │
│   (React Native)   │    │   (Primaire)       │    │   (NLP/ML)         │
└────────────────────┘    └────────────────────┘    └────────────────────┘
        │                        │                        │
        │                        │                        │
        ▼                        ▼                        ▼
┌────────────────────┐    ┌────────────────────┐    ┌────────────────────┐
│   Tableau de Bord  │    │   Stockage Fichiers│    │   Blockchain       │
│   Analytics        │    │   (AWS S3)         │    │   (Certificats)    │
└────────────────────┘    └────────────────────┘    └────────────────────┘
```

## 🛠️ Pile Technologique

### **Développement Frontend**
- **React 18.x** - Interface web moderne
- **Material-UI** - Bibliothèque de composants professionnelle
- **React Query** - Gestion des données et cache
- **React Router** - Gestion de la navigation
- **Chart.js** - Visualisation desanalyses d'apprentissage

### **Infrastructure Backend**
- **Spring Boot 3.x** - Framework Java d'entreprise
- **Spring Security** - Authentification et autorisation
- **Spring Data JPA** - Abstraction de la base de données
- **MySQL 8.0** - Base de données principale
- **Redis** - Gestion de cache et sessions

### **IA et Apprentissage Automatique**
- **TensorFlow 2.x** - Framework d'apprentissage automatique
- **Traitement du Langage Naturel** - Analyse de contenu
- **Moteur de Recommandation** - Suggestions personnalisées
- **Analyse d'Apprentissage** - Prédiction des performances

### **Mobile et Multiplateforme**
- **React Native** - Application mobile
- **Expo** - Développement et déploiement
- **Notifications Push** - Engagement des étudiants
- **Support Hors Ligne** - Apprentissage sans connexion

### **Blockchain et Certification**
- **Ethereum** - Contrats intelligents pour certificats
- **IPFS** - Stockage décentralisé de contenu
- **Intégration MetaMask** - Connectivité aux portefeuilles
- **Signatures Numériques** - Validation des certificats

## 🚀 Démarrage Rapide

### **Prérequis**
```bash
# Environnement de développement
Node.js 16+
Java 17+
MySQL 8.0+
Redis 6+
Python 3.9+ (pour les services IA)

# Optionnel
Docker & Docker Compose
Kubernetes (pour la production)
```

### **Installation**

1. **Cloner le Dépôt**
```bash
git clone https://github.com/Delmat237/edusmart-platform.git
cd edusmart-platform
```

2. **Configuration Backend**
```bash
cd backend
./mvnw clean install
./mvnw spring-boot:run
```

3. **Configuration Frontend**
```bash
cd frontend
npm install
npm start
```

4. **Configuration des Services IA**
```bash
cd ai-services
pip install -r requirements.txt
python app.py
```

5. **Déploiement Docker**
```bash
docker-compose up --build
```

### **Configuration de la Base de Données**
```sql
CREATE DATABASE edusmart_db;
CREATE USER 'edusmart_user'@'localhost' IDENTIFIED BY 'secure_password';
GRANT ALL PRIVILEGES ON edusmart_db.* TO 'edusmart_user'@'localhost';
FLUSH PRIVILEGES;
```

## 📚 Aperçu des Fonctionnalités

### **Expérience Étudiant**

#### **Tableau de Bord Personnalisé**
- **Progrès d'Apprentissage** - Suivi visuel des progrès
- **Cours Recommandés** - Suggestions IA
- **Échéances à Venir** - Rappels pour les devoirs
- **Galerie de Réalisations** - Badges et certificats obtenus

#### **Apprentissage Adaptatif**
- **Évaluation des Compétences** - Évaluation initiale des connaissances
- **Contenu Dynamique** - Ajustement selon les performances
- **Rythme d'Apprentissage** - Apprentissage autonome ou structuré
- **Échelle de Difficulté** - Ajustement automatique du contenu

#### **Contenu Interactif**
- **Conférences Vidéo** - Contenu éducatif de haute qualité
- **Quiz Interactifs** - Retour immédiat
- **Laboratoires Virtuels** - Environnements de pratique
- **Forums de Discussion** - Apprentissage collaboratif

### influential **Outils pour Enseignants**

#### **Création de Cours**
- **Constructeur Glisser-Déposer** - Création intuitive de contenu
- **Support Multimédia** - Vidéos, images, documents
- **Outils d'Évaluation** - Quiz, devoirs, examens
- **Intégration d'Analytique** - Aperçus des performances des étudiants

#### **Gestion des Étudiants**
- **Suivi des Progrès** - Suivi en temps réel des étudiants
- **Correction Automatisée** - Évaluation alimentée par l'IA
- **Outils de Communication** - Messagerie et annonces
- **Alertes d'Intervention** - Identification des étudiants à risque

### **Fonctionnalités Administratives**

#### **Gestion des Institutions**
- **Gestion des Rôles Utilisateur** - Étudiants, enseignants, administrateurs
- **Catalogue de Cours** - Bibliothèque centralisée de contenus
- **Système de Rapports** - Analytique complète
- **API d'Intégration** - Connectivité avec systèmes tiers

## 🤖 Fonctionnalités IA

### **Moteur de Recommandation**
```python
# Recommandation de parcours d'apprentissage
def recommend_learning_path(student_profile):
    """
    Recommandation de parcours d'apprentissage basé sur l'IA
    en fonction des compétences, objectifs et performances des étudiants
    """
    skills = analyze_student_skills(student_profile)
    goals = extract_learning_goals(student_profile)
    performance = get_historical_performance(student_profile)
    
    return ml_model.predict_optimal_path(skills, goals, performance)
```

### **Adaptation du Contenu**
```python
# Ajustement dynamique de la difficulté du contenu
def adapt_content_difficulty(student_id, content_id):
    """
    Ajuste automatiquement la difficulté du contenu
    en fonction des performances et du rythme d'apprentissage
    """
    performance = get_student_performance(student_id)
    learning_pace = calculate_learning_pace(student_id)
    
    return content_adapter.adjust_difficulty(
        content_id, performance, learning_pace
    )
```

### **Traitement du Langage Naturel**
```python
# Traitement de contenu multilingue
def process_multilingual_content(content, target_language):
    """
    Traite et traduit le contenu éducatif
    tout en maintenant le contexte éducatif
    """
    translated = translate_content(content, target_language)
    contextualized = adapt_cultural_context(translated, target_language)
    
    return contextualized
```

## 📊 Documentation API

### **Authentification**
```bash
POST /api/auth/login
Content-Type: application/json

{
  "email": "etudiant@example.com",
  "password": "mot_de_passe_sécurisé"
}
来到了

### **Gestion des Cours**
```bash
GET /api/courses
Authorization: Bearer <token>

# Réponse
{
  "courses": [
    {
      "id": 1,
      "title": "Introduction à la Programmation",
      "description": "Apprendre les fondamentaux de la programmation",
      "language": "fr",
      "difficulty": "débutant",
      "duration": "40 heures",
      "instructor": "Jean Dupont",
      "enrolled": 150,
      "rating": 4.8
    }
  ]
}
```

### **Analyse d'Apprentissage**
```bash
GET /api/analytics/student/{studentId}
Authorization: Bearer <token>

# Réponse
{
  "student_id": 123,
  "overall_progress": 75,
  "completed_courses": 8,
  "current_courses": 3,
  "learning_streak": 15,
  "skill_levels": {
    "programming": 85,
    "mathematics": 70,
    "data_science": 60
  },
  "recommended_actions": [
    "Compléter les fondamentaux de Python",
    "Pratiquer les structures de données",
    "Rejoindre un groupe d'étude pour les algorithmes"
  ],
  "achievements": [
    {
      "id": "first_course",
      "title": "Premier Cours Terminé",
      "earned_date": "2024-01-15"
    }
  ]
}
```

### **Recommandations IA**
```bash
GET /api/ai/recommendations/{studentId}
Authorization: Bearer <token>

# Réponse
{
  "learning_path": [
    {
      "course_id": 45,
      "title": "JavaScript Avancé",
      "reason": "Basé sur vos progrès en JavaScript de base",
      "confidence": 0.89
    }
  ],
  "content_suggestions": [
    {
      "type": "video",
      "title": "Programmation Asynchrone Expliquée",
      "duration": "15 min",
      "relevance": 0.92
    }
  ]
}
```

## 🎮 Système de Gamification

### **Système de Récompenses**
```javascript
// Définitions des récompenses
const achievements = {
  'first_login': {
    title: 'Bienvenue à Bord !',
    description: 'Compléter votre première connexion',
    points: 10,
    badge: 'welcome.png'
  },
  'streak_7': {
    title: 'Guerrier de la Semaine',
    description: 'Étudier pendant 7 jours consécutifs',
    points: 100,
    badge: 'streak_7.png'
  },
  'course_complete': {
    title: 'Maître du Cours',
    description: 'Terminer votre premier cours',
    points: 500,
    badge: 'graduate.png'
  }
};
```

### **Système de Classement**
```sql
-- Requête pour le classement hebdomadaire
SELECT 
    u.id,
    u.full_name,
    u.avatar,
    SUM(a.points) as total_points,
    COUNT(DISTINCT c.id) as courses_completed
FROM users u
LEFT JOIN achievements a ON u.id = a.student_id
LEFT JOIN course_completions c ON u.id = c.student_id
WHERE a.earned_date >= DATE_SUB(NOW(), INTERVAL 7 DAY)
GROUP BY u.id
ORDER BY total_points DESC
LIMIT 10;
```

## 🔐 Fonctionnalités de Sécurité

### **Authentification et Autorisation**
- **Authentification JWT** - Accès sécurisé à l'API
- **Contrôle d'Accès Basé sur les Rôles** - Rôles étudiant, enseignant, administrateur
- **Authentification Multi-Facteurs** - Sécurité renforcée
- **Intégration OAuth** - Connexion via Google, Facebook, Microsoft

### **Protection des Données**
- **Conformité RGPD** - Normes européennes de protection des données
- **Chiffrement des Données** - AES-256 au repos
- **Communications Sécurisées** - TLS 1.3 pour toutes les connexions
- **Contrôles de Confidentialité** - Paramètres de confidentialité granulaires

### **Sécurité du Contenu**
- **Protection DRM** - Gestion des droits numériques
- **Filigrane** - Protection de la propriété du contenu
- **Contrôle d'Accès** - Accès limité dans le temps au contenu
- **Prévention du Piratage** - Mesures de sécurité avancées

## 🌍 Localisation et Accessibilité

### **Support Multilingue**
```javascript
// Configuration des langues
const languages = {
  'en': 'Anglais',
  'fr': 'Français',
  'sw': 'Kiswahili',
  'ha': 'Hausa',
  'yo': 'Yoruba',
  'am': 'አማርኛ (Amharic)'
};

// Traduction dynamique du contenu
const translateContent = async (content, targetLang) => {
  const response = await fetch('/api/translate', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ content, targetLang })
  });
  return response.json();
};
```

### **Fonctionnalités d'Accessibilité**
- **Support pour Lecteurs d'Écran** - Étiquettes et descriptions ARIA
- **Navigation au Clavier** - Accessibilité complète au clavier
- **Mode Contraste Élevé** - Accessibilité visuelle
- **Synthèse Vocale** - Livraison de contenu audio
- **Tailles de Police Ajustables** - Personnalisation visuelle

## 📱 Application Mobile

### **Fonctionnalités React Native**
```javascript
// Support d'apprentissage hors ligne
import { NetInfo } from '@react-native-async-storage/async-storage';

const OfflineLearning = () => {
  const [isConnected, setIsConnected] = useState(true);
  
  useEffect(() => {
    const unsubscribe = NetInfo.addEventListener(state => {
      setIsConnected(state.isConnected);
    });
    return unsubscribe;
  }, []);
  
  const downloadCourseContent = async (courseId) => {
    try {
      const content = await CourseAPI.downloadOfflineContent(courseId);
      await AsyncStorage.setItem(`course_${courseId}`, JSON.stringify(content));
    } catch (error) {
      console.error('Échec du téléchargement :', error);
    }
  };
};
```

### **Notifications Push**
```javascript
// Rappels d'apprentissage
const scheduleStudyReminder = (studentId, preferences) => {
  const message = {
    title: 'Temps d'Apprendre ! 📚',
    body: 'Votre session d'apprentissage quotidienne est prête',
    data: {
      type: 'study_reminder',
      studentId: studentId
    }
  };
  
  PushNotification.localNotificationSchedule({
    ...message,
    date: new Date(Date.now() + preferences.reminderInterval)
  });
};
```

## 🔗 Intégration Blockchain

### **Contrat Intelligent de Certification**
```solidity
// Contrat de certificat simplifié
pragma solidity ^0.8.0;

contract EduSmartCertificate {
    struct Certificate {
        uint256 id;
        address student;
        string courseName;
        string issuer;
        uint256 issueDate;
        bytes32 credentialHash;
    }
    
    mapping(uint256 => Certificate) public certificates;
    mapping(address => uint256[]) public studentCertificates;
    
    event CertificateIssued(
        uint256 indexed certificateId,
        address indexed student,
        string courseName
    );
    
    function issueCertificate(
        address _student,
        string memory _courseName,
        string memory _issuer,
        bytes32 _credentialHash
    ) public {
        uint256 certificateId = block.timestamp;
        
        certificates[certificateId] = Certificate({
            id: certificateId,
            student: _student,
            courseName: _courseName,
            issuer: _issuer,
            issueDate: block.timestamp,
            credentialHash: _credentialHash
        });
        
        studentCertificates[_student].push(certificateId);
        
        emit CertificateIssued(certificateId, _student, _courseName);
    }
}
```

## 📊 Analyses et Rapports

### **Tableau de Bord d'Analyse d'Apprentissage**
```javascript
// Analyse des performances des étudiants
const LearningAnalytics = () => {
  const [analytics, setAnalytics] = useState({});
  
  const fetchAnalytics = async (studentId) => {
    const data = await AnalyticsAPI.getStudentAnalytics(studentId);
    setAnalytics(data);
  };
  
  return (
    <div className="analytics-dashboard">
      <MetricCard
        title="Progrès d'Apprentissage"
        value={`${analytics.progress}%`}
        trend={analytics.progressTrend}
      />
      <ChartComponent
        data={analytics.performanceData}
        type="line"
        title="Performance au Fil du Temps"
      />
      <RecommendationList
        recommendations={analytics.recommendations}
      />
    </div>
  );
};
```

### **Rapports Institutionnels**
```sql
-- Rapport mensuel d'apprentissage
SELECT 
    DATE_FORMAT(created_at, '%Y-%m') as month,
    COUNT(DISTINCT student_id) as active_students,
    AVG(completion_rate) as avg_completion_rate,
    SUM(learning_hours Ascending
```

### **Stratégie de Tests**

### **Tests Unitaires**
```javascript
// Tests de composants React
import { render, screen, fireEvent } from '@testing-library/react';
import { CourseCard } from '../components/CourseCard';

describe('CourseCard', () => {
  const mockCourse = {
    id: 1,
    title: 'Cours Test',
    description: 'Description Test',
    instructor: 'Enseignant Test'
  };
  
  test('affiche correctement les informations du cours', () => {
    render(<CourseCard course={mockCourse} />);
    
    expect(screen.getByText('Cours Test')).toBeInTheDocument();
    expect(screen.getByText('Enseignant Test')).toBeInTheDocument();
  });
  
  test('gère le clic d'inscription', () => {
    const mockEnroll = jest.fn();
    render(<CourseCard course={mockCourse} onEnroll={mockEnroll} />);
    
    fireEvent.click(screen.getByText('Inscrire Maintenant'));
    expect(mockEnroll).toHaveBeenCalledWith(1);
  });
});
```

### **Tests d'Intégration**
```java
// Test d'intégration Spring Boot
@SpringBootTest
@AutoConfigureTestDatabase
class CourseServiceIntegrationTest {
    
    @Autowired
    private CourseService courseService;
    
    @Test
    void shouldCreateCourseSuccessfully() {
        // Données
        CourseDTO courseDTO = new CourseDTO();
        courseDTO.setTitle("Cours Test");
        courseDTO.setDescription("Description Test");
        
        // Quand
        Course created = courseService.createCourse(courseDTO);
        
        // Alors
        assertThat(created.getId()).isNotNull();
        assertThat(created.getTitle()).isEqualTo("Cours Test");
    }
}
```

## 🚀 Guide de Déploiement

### **Environnement de Production**
```yaml
# docker-compose.prod.yml
version: '3.8'
services:
  backend:
    image: edusmart/backend:latest
    environment:
      - SPRING_PROFILES_ACTIVE=production
      - DATABASE_URL=jdbc:mysql://db:3306/edusmart_prod
      - REDIS_URL=redis://redis:6379
    depends_on:
      - db
      - redis
  
  frontend:
    image: edusmart/frontend:latest
    ports:
      - "80:80"
      - "443:443"
    volumes:
      - ./ssl:/etc/nginx/ssl
  
  db:
    image: mysql:8.0
    environment:
      - MYSQL_ROOT_PASSWORD=secure_root_password
      - MYSQL_DATABASE=edusmart_prod
    volumes:
      - db_data:/var/lib/mysql
  
  redis:
    image: redis:7-alpine
    volumes:
      - redis_data:/data

volumes:
  db_data:
  redis_data:
```

### **Configuration Kubernetes**
```yaml
# k8s/deployment.yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: edusmart-backend
spec:
  replicas: 3
  selector:
    matchLabels:
      app: edusmart-backend
  template:
    metadata:
      labels:
        app: edusmart-backend
    spec:
      containers:
      - name: backend
        image: edusmart/backend:latest
        ports:
        - containerPort: 8080
        env:
        - name: DATABASE_URL
          valueFrom:
            secretKeyRef:
              name: db-secret
              key: url
        resources:
          requests:
            memory: "512Mi"
            cpu: "250m"
          limits:
            memory: "1Gi"
            cpu: "500m"
```

## 🤝 Contribution

### **Flux de Développement**
1. **Forker** le dépôt
2. **Créer** une branche de fonctionnalité (`git checkout -b feature/apprentissage-adaptatif`)
3. **Implémenter** les changements avec des tests
4. **Exécuter** les vérifications de qualité (`npm run lint`, `mvn test`)
5. **Valider** avec des commits conventionnels
6. **Pousser** et créer une Pull Request

### **Normes de Code**
- **Backend** : Suivre les meilleures pratiques de Spring Boot
- **Frontend** : Utiliser ESLint et Prettier
- **Base de Données** : Suivre les principes de normalisation
- **API** : Conception RESTful avec documentation OpenAPI
- **Sécurité** : Conformité aux directives OWASP

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

## 🏆 Remerciements

- **Union Africaine** pour les initiatives de développement éducatif
- **UNESCO** pour les normes éducatives mondiales
- **Communautés open source** pour les outils et bibliothèques incroyables
- **Institutions éducatives** pour les tests et retours
- **Étudiants et éducateurs** pour leurs précieuses contributions

## 👨‍💻 Auteur

**Leonel Azangue (Delmat237)**  
- **GitHub** : [@Delmat237](https://github.com/Delmat237)  
- **LinkedIn** : [leonel-azangue](https://www.linkedin.com/in/leonel-azangue)  
- **Email** : azangueleonel9@gmail.com  

---

🌍 **Renforcer l'éducation africaine grâce à la technologie**

⭐ **Ajoutez une étoile à ce dépôt pour soutenir l'innovation éducative en Afrique !**
