# ⚛ ElectroLab AI — Android Mobile Workstation & Appium Automated Testing

This repository contains the complete Android application source code, Appium mobile automated test framework, pre-compiled APK, 530 Mobile QA Test Cases report, Baseline Load Testing Certification Report, and the **530 OWASP Vulnerability & Security Report** for **ElectroLab AI**.

---

## 📱 What's Inside

1. **`android-app/`**: Native Android Studio project targeting Android SDK 35 (Android 14/15) with Hardware-Accelerated WebView and full-screen workstation suite.
2. **`ElectroLab-AI-Corrosion.apk`**: Pre-compiled, ready-to-install Android package (8.03 MB).
3. **`testing/appium/`**: Appium automated end-to-end mobile test framework for Android UiAutomator2.
4. **`testing/load_testing/`**: Baseline load testing suite simulating 100 concurrent virtual users across Web and Mobile App API endpoints for 60 seconds continuous load.
5. **`testing/security/`**: OWASP API Security testing suite evaluating 530 vulnerability attack vectors and input validation probes.
6. **`ElectroLab_AI_Vulnerability_Security_Report_500.xlsx`**: Master 530 OWASP API Security Test Cases workbook.
7. **`ElectroLab_AI_Load_Testing_Report.xlsx`**: Master Baseline Load Testing Report (100 VU, 60s, 121.9 RPS).
8. **`ElectroLab_AI_Mobile_Comprehensive_Test_Report_500.xlsx`**: Master Mobile Quality Assurance report containing **530 verified passing test cases** across 7 test categories.

---

## 🔒 OWASP API Vulnerability & Security Assessment

- **Total Test Cases**: **530 Security Test Cases**
- **Defended / Compliant**: **512 Tests (96.6%)**
- **Hardened / Remediated**: **18 Safeguards (3.4%)**
- **Critical Vulnerabilities**: **0 (Zero)**
- **Security Grade**: **Grade A- (Hardened & Protected)**

---

## 📊 Baseline & Load Testing Performance Certification

- **Total Requests Handled**: **5,817 Requests** in 60 seconds
- **Throughput (RPS)**: **92.9 - 121.9 req/sec**
- **Fastest Response (Min)**: **33.28 ms**
- **Average Response Time**: **993.88 ms**
- **Median Response Time (P50)**: **982.85 ms**
- **P95 Response Time**: **1,533.62 ms (1.5s)**
- **Reliability / Success Rate**: **100.00% (0 errors)**

---

## 🚀 Running Tests

### Security Vulnerability Probes:
```bash
python testing/security/run_vulnerability_tests.py
```

### Baseline Load Testing:
```bash
python testing/load_testing/run_baseline_load_test.py
```

### Appium Mobile Functional Tests:
```bash
cd testing/appium
npm install
npm test
```

---

## 📲 Installing on Android Phone

- Download `ElectroLab-AI-Corrosion.apk` directly to your Android device and tap **Install**.
- Target SDK: 35 | Minimum SDK: 24 (Android 7.0+)
