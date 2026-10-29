# ⚛ ElectroLab AI — Android Mobile Workstation & Appium Automated Testing

This repository contains the complete Android application source code, Appium mobile automated test framework, pre-compiled APK, 530 Mobile QA Test Cases report, and the **Baseline Load Testing Certification Report** for **ElectroLab AI**.

---

## 📱 What's Inside

1. **`android-app/`**: Native Android Studio project targeting Android SDK 35 (Android 14/15) with Hardware-Accelerated WebView and full-screen workstation suite.
2. **`ElectroLab-AI-Corrosion.apk`**: Pre-compiled, ready-to-install Android package (8.03 MB).
3. **`testing/appium/`**: Appium automated end-to-end mobile test framework for Android UiAutomator2.
4. **`testing/load_testing/`**: Baseline load testing suite simulating 100 concurrent virtual users across Web and Mobile App API endpoints for 60 seconds continuous load.
5. **`ElectroLab_AI_Load_Testing_Report.xlsx`**: Master Baseline Load Testing Report with throughput, response times, second-by-second analytics, and trace audits.
6. **`ElectroLab_AI_Mobile_Comprehensive_Test_Report_500.xlsx`**: Master Mobile Quality Assurance report containing **530 verified passing test cases** across 7 test categories.

---

## 📊 Baseline & Load Testing Performance Certification

The mobile app API integration and backend endpoints underwent rigorous baseline load testing simulating 100 concurrent virtual users continuously for 1 minute (60 seconds).

### 🎯 Key Performance Results:
- **Total Requests Handled**: **5,817 Requests** in 60 seconds
- **Throughput (RPS)**: **92.9 - 121.9 req/sec**
- **Fastest Response (Min)**: **33.28 ms**
- **Average Response Time**: **993.88 ms**
- **Median Response Time (P50)**: **982.85 ms**
- **P95 Response Time**: **1,533.62 ms (1.5s)**
- **Slowest Response Time (Max)**: **2,382.98 ms (2.3s)**
- **Reliability / Success Rate**: **100.00% (0 errors)**

### 📈 Master Load Testing Excel Report:
- Complete Excel report available at: [`ElectroLab_AI_Load_Testing_Report.xlsx`](./ElectroLab_AI_Load_Testing_Report.xlsx)

---

## 🚀 Running Tests

### Appium Mobile Functional Tests:
```bash
cd testing/appium
npm install
npm test
```

### Baseline Load Testing:
```bash
python testing/load_testing/run_baseline_load_test.py
```

---

## 📲 Installing on Android Phone

- Download `ElectroLab-AI-Corrosion.apk` directly to your Android device and tap **Install**.
- Target SDK: 35 | Minimum SDK: 24 (Android 7.0+)
