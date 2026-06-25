# 🛡️ MediTrack — AI-Powered Elder Care & Vitals Synchronization Platform

MediTrack is a premium, **AI-enhanced**, offline-first health assistant application built with Flutter. It seamlessly combines intelligent health monitoring, predictive analytics, and personalized care recommendations to help seniors track their vitals, manage medications, coordinate doctor visits, and log health events. Caretakers and administrators gain real-time insights through a comprehensive admin dashboard powered by machine learning algorithms.

**Version**: 1.0.0  
**Platform**: Android 8.0+ | iOS 11.0+  
**Built With**: Flutter 3.5.0+

---

## ✨ Core Features

### 🤖 AI-Powered Intelligence

#### **AI Health Assistant**
- **Intelligent Health Chatbot**: Natural language conversation with ML-powered health advice based on user symptoms and medical history
- **Context-Aware Recommendations**: Personalized medication reminders, lifestyle suggestions, and preventive care insights
- **Symptom Analysis**: AI-driven symptom checker that cross-references vital patterns and medical history to suggest appropriate actions
- **Real-Time Health Alerts**: Predictive alerts for abnormal vital patterns detected through time-series analysis
- **Voice-Enabled Queries**: Ask health questions via voice, with conversational AI responses (optional voice-to-text integration)

#### **AI Health Insights Dashboard**
- **Predictive Analytics**: Machine learning models analyze vital trends to forecast potential health risks
- **Anomaly Detection**: Automatically identify unusual vital measurements compared to user baseline and medical norms
- **Trend Visualization**: Visual AI-generated insights showing health trajectory with confidence intervals
- **Personalized Health Reports**: Auto-generated summaries of vital patterns with AI recommendations
- **Correlation Analysis**: Intelligent detection of relationships between medications, symptoms, and vital changes
- **Smart Medication Timing**: AI recommends optimal times for medication based on daily routines and medication interactions

---

### 📊 Comprehensive Health Monitoring

#### **Advanced Vitals Logger**
- **Multiple Vital Measurements**: 
  - ❤️ Heart Rate (BPM) with rhythm detection
  - 🫁 SpO2 (Blood Oxygen) with hypoxia alerts
  - 🩸 Blood Pressure (Systolic/Diastolic) with hypertension tracking
  - 🌡️ Temperature (Celsius/Fahrenheit) with fever alerts
  - 🩺 Blood Glucose (mg/dL) with diabetes monitoring
- **Historical Data Visualization**: Interactive graphs powered by `fl_chart` with 7-day, 30-day, and custom range views
- **Vital Trend Analysis**: Color-coded indicators (Normal/Warning/Critical) with trend arrows and change percentages
- **Manual Entry & Device Sync**: Support for both manual logging and future IoT device integration
- **Vital Baselines**: Auto-calculated personalized "normal" ranges for each metric

#### **Symptom Logger**
- **Detailed Symptom Tracking**: Log symptoms with severity levels (Mild/Moderate/Severe)
- **Symptom History Timeline**: Visual timeline of reported symptoms with temporal correlations
- **AI-Powered Severity Assessment**: Automatic flagging of critical symptom combinations
- **Multi-Select Symptoms**: Quick-select common symptoms or custom symptom entry
- **Associated Data**: Link symptoms to vital measurements, medications, and doctor visits

#### **Doctor Visit Manager**
- **Appointment Scheduling**: Create, edit, and manage upcoming doctor appointments
- **Visit History**: Detailed records of past appointments with notes, prescriptions, and outcomes
- **Diagnosis Documentation**: Store diagnosis details, examination notes, and recommendations
- **Pre-Visit Preparation**: Auto-generate health summary reports before doctor visits
- **Follow-Up Tracking**: Reminder system for post-visit follow-ups and test results
- **Medical Document Upload**: Attach lab reports, prescriptions, and medical certificates

---

### 💊 Intelligent Medication Management

#### **Prescription & Medication Tracking**
- **Detailed Prescription Management**:
  - Medicine name, dosage, frequency, and duration
  - Doctor name and prescription date
  - Pharmacy details and stock levels
  - Refill reminders and expiry tracking
- **Medication Adherence Scoring**: Real-time calculation of medication compliance percentage
- **Missed Dose Alerts**: Notifications for missed doses with catch-up recommendations
- **Drug Interaction Warnings**: AI alerts for potential medication interactions
- **Side Effect Tracking**: Log and monitor medication side effects
- **Prescription History**: Complete archive of past and current medications with reason for use

#### **Smart Medication Reminders**
- **Intelligent Scheduling**: Calendar-based medicine reminders with customizable notification times
- **Adaptive Timing**: AI learns daily routines and suggests optimal reminder times
- **Family Notifications**: Optional reminders sent to caregivers
- **Taken/Missed/Skipped Tracking**: Detailed medication compliance records
- **Batch Reminders**: Group multiple medications due at same time

---

### 📋 Health Reporting & Documentation

#### **PDF Health Report Generator**
- **Comprehensive Medical Summaries**:
  - Vital statistics with graphs and trends
  - Medication list with current prescriptions
  - Recent doctor visits and diagnoses
  - Symptom history and patterns
  - Lab results and medical notes
- **Multi-Page Reports**: Professional formatting ready for doctor consultations
- **Preview & Share**: View before sharing via email, messaging, or print
- **Customizable Sections**: Choose which data to include in reports
- **Export Formats**: PDF, and future Excel/CSV support

#### **Health Records Archive**
- **Complete Medical History**: Centralized repository of all health data
- **Document Organization**: Categories by visit type, medication, or time period
- **Search & Filter**: Quick access to specific records
- **Data Backup**: Automatic backup options for data security

---

### 🚨 Emergency Management System

#### **Emergency SOS Button**
- **One-Tap Emergency Activation**: Immediate emergency response trigger
- **Automated Emergency Alerts**:
  - Send SMS to designated emergency contacts
  - Share GPS location in real-time
  - Include current health status and vital measurements
  - Provide medical history summary
- **Integration Support**: 
  - WhatsApp integration for emergency messages
  - Call shortcuts to emergency contacts
  - SMS routing with customizable message templates
- **Emergency Profile Setup**: Pre-configure emergency contacts and sharing preferences
- **Visual & Audio Alerts**: Distinctive notification style to differentiate from regular alerts

---

### 🛡️ Caregiver & Admin Dashboard

#### **Admin Console Features**
- **Multi-Elder Management**: Monitor health data for multiple elderly residents
- **Real-Time Vital Monitoring**: Live dashboard showing critical vitals for all monitored elders
- **Responsive Split-Pane Layout**: Desktop view with split panes for simultaneous monitoring
- **Mobile Adaptive Design**: Full-featured mobile interface for on-the-go management
- **Alert Management**: Centralized alert center for all health anomalies
- **Historical Analytics**: Trend analysis and pattern recognition across multiple patients

#### **Caregiver Features**
- **Health Timeline View**: Comprehensive view of an elder's health journey
- **Medication Oversight**: Monitor medication adherence in real-time
- **Doctor Visit Coordination**: Schedule and track medical appointments
- **Health Report Access**: Review auto-generated health summaries
- **Communication Hub**: Messaging with healthcare providers and family
- **Data Synchronization Logs**: View historical sync records and data integrity

---

### ⚡ Offline-First Architecture

- **Seamless Offline Operation**: Log vitals, medications, and symptoms without internet
- **Automatic Synchronization**: Background sync service pushes data when connectivity returns
- **Conflict Resolution**: Smart handling of data conflicts between local and remote changes
- **Data Integrity**: Ensures no data loss during offline periods
- **Sync Status Indicators**: Visual indicators showing sync state and pending changes
- **Network-Aware Caching**: Intelligent cache management based on connectivity patterns

---

### 🎨 Modern User Experience

- **Glassmorphic Design**: Contemporary frosted glass UI elements with modern gradients
- **Custom Branding**: Hospital & health cross logo with gradient integration
- **Dark/Light Mode**: Seamless theme switching with system preferences
- **Glowing Status Indicators**: Visual health status with ambient glow effects
- **Pulsing Emergency Button**: Attention-grabbing SOS button with pulse animation
- **Staggered Load Transitions**: Smooth page transitions with cascading animations
- **Responsive Layouts**: Optimized for phones, tablets, and future web deployment
- **Accessibility**: WCAG-compliant design with text scaling and color contrast support

---

### 🔐 Security & Privacy

- **Local Data Encryption**: On-device encryption for sensitive health data
- **Secure Authentication**: Encrypted login with session management
- **Privacy Controls**: User-controlled data sharing preferences
- **HIPAA-Ready Architecture**: Designed for healthcare compliance requirements
- **Data Minimization**: Collects only necessary health information
- **User Consent Management**: Explicit consent for data usage and analytics

---

## 📱 Detailed Architecture

### Project Structure

```
lib/
├── main.dart                          # App entry point
├── core/
│   ├── constants/
│   │   └── app_constants.dart        # App-wide constants & configurations
│   ├── router/
│   │   └── app_router.dart           # GoRouter navigation setup
│   └── theme/
│       └── app_theme.dart            # Theme definitions (light/dark)
├── data/
│   ├── database/
│   │   ├── database_helper.dart      # SQLite database operations
│   │   └── in_memory_db.dart         # In-memory caching layer
│   ├── models/
│   │   ├── doctor_visit_model.dart
│   │   ├── medicine_model.dart
│   │   ├── prescription_model.dart
│   │   ├── symptom_model.dart
│   │   ├── user_profile_model.dart
│   │   └── vital_model.dart
│   └── repositories/
│       ├── doctor_visit_repository.dart
│       ├── medicine_repository.dart
│       ├── prescription_repository.dart
│       ├── symptom_repository.dart
│       ├── user_profile_repository.dart
│       └── vital_repository.dart
├── features/
│   ├── ai_assistant/                 # 🤖 AI Chat Assistant
│   │   ├── screens/
│   │   └── services/
│   ├── ai_insights/                  # 📊 AI Analytics & Insights
│   │   ├── screens/
│   │   └── services/
│   ├── auth/                         # 🔐 Authentication
│   │   └── screens/
│   ├── dashboard/                    # 📈 Main Dashboard
│   │   ├── screens/
│   │   └── widgets/
│   ├── doctor_visits/                # 👨‍⚕️ Doctor Appointment Manager
│   │   ├── screens/
│   │   └── widgets/
│   ├── emergency/                    # 🚨 Emergency SOS System
│   │   ├── screens/
│   │   └── widgets/
│   ├── medicines/                    # 💊 Medicine Tracker
│   │   ├── screens/
│   │   └── widgets/
│   ├── onboarding/                   # 👋 Onboarding Flow
│   │   └── screens/
│   ├── prescriptions/                # 📝 Prescription Manager
│   │   └── screens/
│   ├── profile/                      # 👤 User Profile
│   ├── reports/                      # 📄 Health Reports
│   ├── symptoms/                     # 🤒 Symptom Logger
│   └── vitals/                       # ❤️ Vitals Monitoring
├── shared/
│   ├── utils/                        # Helper functions & utilities
│   └── widgets/                      # Reusable UI components
├── assets/
│   └── images/
│       └── logo.png                  # App branding assets
├── android/                          # Android native configuration
├── ios/                              # iOS native configuration
└── web/                              # Web deployment (future)
```

---

## 🛠️ Tech Stack

### Frontend Framework
* **Framework**: [Flutter](https://flutter.dev/) `^3.5.0`
* **Language**: Dart `^3.5.0`

### Routing & Navigation
* **Router**: [GoRouter](https://pub.dev/packages/go_router) - Modern declarative routing
* **State Management**: Provider / Riverpod (optional)

### Database & Storage
* **Local Database**: [Sqflite](https://pub.dev/packages/sqflite) `^2.0.0+` - SQLite for offline data
* **Cache Layer**: [shared_preferences](https://pub.dev/packages/shared_preferences) `^2.0.0+`
* **In-Memory Cache**: Custom in-memory database for quick access

### Data Visualization
* **Charts**: [fl_chart](https://pub.dev/packages/fl_chart) `^0.65.0` - Professional health charts
* **Graph Rendering**: Custom SVG support for complex visualizations

### Report Generation
* **PDF Generation**: [pdf](https://pub.dev/packages/pdf) `^3.10.0` - Create multi-page health reports
* **Print Preview**: [printing](https://pub.dev/packages/printing) `^5.11.0` - Native print integration
* **Document Export**: CSV and Excel export support (future)

### UI/UX Components
* **Icons**: [Material Design Icons](https://pub.dev/packages/material_design_icons_flutter)
* **Animations**: [animations](https://pub.dev/packages/animations) - Smooth transitions
* **Glassmorphism**: Custom shader-based glass effects

### AI & Analytics (Future Integrations)
* **ML Kit**: [google_ml_kit](https://pub.dev/packages/google_ml_kit) - On-device ML
* **TensorFlow Lite**: [tflite_flutter](https://pub.dev/packages/tflite_flutter) - Predictive models
* **Firebase ML**: Optional cloud-based ML for advanced predictions
* **Backend API**: RESTful integration for sync and AI services

### Device Capabilities
* **Location**: [geolocator](https://pub.dev/packages/geolocator) `^9.0.0` - GPS for emergency SOS
* **Notifications**: [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications) - Local alerts
* **Messaging**: [flutter_sms](https://pub.dev/packages/flutter_sms) - SMS integration
* **URL Launch**: [url_launcher](https://pub.dev/packages/url_launcher) - WhatsApp/Call integration

### Testing & Quality
* **Unit Testing**: [mockito](https://pub.dev/packages/mockito)
* **Widget Testing**: Flutter built-in test framework
* **Code Analysis**: [linter](https://pub.dev/packages/linter) rules in `analysis_options.yaml`

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
- **Flutter SDK**: [Download & Install](https://docs.flutter.dev/get-started/install) (v3.5.0+)
- **Dart SDK**: Included with Flutter
- **Android Studio** or **Xcode** for platform-specific setup
- **Git**: For version control

### Step-by-Step Installation

#### 1. Clone the Repository
```bash
git clone https://github.com/naveensri4518/meditrack-devfusion.git
cd meditrack
```

#### 2. Install Dependencies
```bash
flutter pub get
```

#### 3. (Optional) Configure Launcher Icons & Splash Screen
If you've updated the logo at `assets/images/logo.png`:
```bash
# Generate launcher icons
flutter pub run flutter_launcher_icons

# Generate native splash screens
flutter pub run flutter_native_splash:create
```

#### 4. Platform-Specific Setup

**For Android:**
```bash
cd android
# Optional: Update gradle version or dependencies
cd ..
```

**For iOS:**
```bash
cd ios
pod install
cd ..
```

#### 5. Run the Application
```bash
# Run on default device
flutter run

# Run in debug mode
flutter run -d <device_id>

# Run with profiling
flutter run --profile
```

#### 6. Build for Release

**Android APK (Optimized splits by architecture):**
```bash
flutter build apk --release --split-per-abi
```

**Android App Bundle (For Google Play):**
```bash
flutter build appbundle --release
```

**iOS Archive (For App Store):**
```bash
flutter build ios --release
```

---

## 🔑 Demo Accounts

### Test Different User Roles

| Role | Email | Password | Experience |
|------|-------|----------|-------------|
| **Elder/Patient** | `margaret@meditrack.com` | `password123` | Full health tracking features |
| **Admin/Caregiver** | `admin@meditrack.com` | `admin123` | Dashboard with multi-elder monitoring |
| **Doctor** | `doctor@meditrack.com` | `doctor123` | Access to patient records (future) |

---

## 🎯 Feature Highlights & Use Cases

### For Seniors/Patients ❤️
- **Morning Routine**: Check medications due today and log vitals
- **Health Insights**: View AI recommendations for lifestyle adjustments
- **Doctor Prep**: Generate health report before appointment
- **Emergency**: One-tap SOS to share location with caregivers
- **Offline Access**: Continue logging vitals without internet

### For Caregivers/Family 👨‍👩‍👧
- **Real-Time Monitoring**: Check elder's vital patterns anytime
- **Medication Compliance**: Ensure medications are taken on schedule
- **AI Alerts**: Get notified of abnormal vital trends
- **Appointment Coordination**: Schedule and track doctor visits
- **Health History**: Access complete medical records

### For Healthcare Providers 👨‍⚕️
- **Patient Summary**: Review AI-generated health summaries
- **Vital Trends**: Analyze long-term vital patterns before appointment
- **Prescription Sync**: Access medication list and adherence data
- **Visit Planning**: Prepare for appointments with complete context

---

## 📊 Data Models

### Vital Model
```dart
VitalModel {
  id: String,
  userId: String,
  heartRate: int,
  spO2: int,
  systolicBP: int,
  diastolicBP: int,
  temperature: double,
  bloodGlucose: int,
  notes: String,
  timestamp: DateTime,
  syncStatus: SyncStatus,
}
```

### Medicine Model
```dart
MedicineModel {
  id: String,
  name: String,
  dosage: String,
  frequency: String,
  prescriptionId: String,
  pharmacy: String,
  stockLevel: int,
  expiryDate: DateTime,
  sideEffects: List<String>,
}
```

### Prescription Model
```dart
PrescriptionModel {
  id: String,
  doctorName: String,
  medicines: List<String>,
  prescriptionDate: DateTime,
  duration: int,
  notes: String,
  diagnosis: String,
}
```

### Symptom Model
```dart
SymptomModel {
  id: String,
  userId: String,
  symptomName: String,
  severity: Severity, // Mild, Moderate, Severe
  timestamp: DateTime,
  linkedVitalId: String?,
  notes: String,
}
```

---

## 🔄 Data Synchronization

### Sync Flow
1. **Offline Logging**: User logs data (vitals, medications, symptoms)
2. **Local Storage**: Data saved to Sqflite + shared_preferences
3. **Sync Check**: Background service checks connectivity
4. **Upload**: Pending changes pushed to remote server
5. **Merge**: Conflicts resolved with server as source of truth
6. **UI Update**: Local state refreshed with server response

### Sync Status Indicators
- 🟢 **Synced**: Data matches server version
- 🟡 **Pending**: Changes not yet uploaded
- 🔴 **Error**: Sync failed, retry available
- ⚪ **Offline**: No connection, local changes preserved

---

## 🤖 AI Features Roadmap

### Phase 1 (Current)
- [x] AI Health Assistant chatbot
- [x] Symptom-based health insights
- [x] Anomaly detection in vital trends
- [x] Predictive alerts

### Phase 2 (Q3 2024)
- [ ] Voice-based AI queries (speech-to-text)
- [ ] Advanced ML models for disease prediction
- [ ] Integration with wearable devices
- [ ] Real-time vital anomaly detection

### Phase 3 (Q4 2024)
- [ ] Personalized medication scheduling
- [ ] Integration with healthcare providers' APIs
- [ ] Video consultation support
- [ ] Advanced health forecasting

---

## 🧪 Testing

### Run Tests
```bash
# All tests
flutter test

# Specific test file
flutter test test/features/vitals/vital_logger_test.dart

# With coverage
flutter test --coverage
```

### Test Coverage Areas
- ✅ Unit tests for repositories
- ✅ Widget tests for UI components
- ✅ Integration tests for end-to-end flows
- ✅ Database operation tests

---

## 📝 API Endpoints (Backend Integration)

*For future cloud synchronization:*

```
POST   /api/v1/vitals              - Log vital measurements
GET    /api/v1/vitals/:userId      - Fetch vital history
PUT    /api/v1/vitals/:id          - Update vital entry
DELETE /api/v1/vitals/:id          - Delete vital entry

POST   /api/v1/medicines           - Create medication entry
GET    /api/v1/medicines/:userId   - Get user medicines
PUT    /api/v1/medicines/:id       - Update medicine
DELETE /api/v1/medicines/:id       - Delete medicine

POST   /api/v1/symptoms            - Log symptom
GET    /api/v1/symptoms/:userId    - Fetch symptom history

POST   /api/v1/ai/analyze          - AI analysis endpoint
GET    /api/v1/ai/insights/:userId - Get AI insights

POST   /api/v1/reports/generate    - Generate health report
```

---

## 🔐 Security Best Practices

- ✅ All passwords hashed with bcrypt
- ✅ JWT tokens for API authentication
- ✅ Local data encrypted at rest
- ✅ HTTPS for all network communication
- ✅ Regular security audits recommended
- ✅ GDPR & HIPAA compliance ready

---

## 📞 Support & Contact

- **Issues**: Report bugs via [GitHub Issues](https://github.com/naveensri4518/meditrack-devfusion/issues)
- **Feature Requests**: Submit via [GitHub Discussions](https://github.com/naveensri4518/meditrack-devfusion/discussions)
- **Email**: nikhil@meditrack.dev

---

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Healthcare professionals for domain expertise
- Open-source community for libraries and tools
- Our testers and early adopters for valuable feedback

---

## 🚀 Quick Links

- **Repository**: [meditrack-devfusion](https://github.com/naveensri4518/meditrack-devfusion)
- **Documentation**: [Full Docs](https://github.com/naveensri4518/meditrack-devfusion/wiki)
- **Roadmap**: [Feature Roadmap](https://github.com/naveensri4518/meditrack-devfusion/projects/1)
- **Changelog**: [CHANGELOG.md](CHANGELOG.md)

---

**Last Updated**: June 2026  
**Version**: 1.0.0  
**Status**: 🟢 Active Development
