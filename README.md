# Host based Firewall Security Lab

## 📌 Objective
Configure and test basic firewall rules to allow or block specific network ports using Windows Defender Firewall.

---

## 🛠 Tools Used
- Windows Defender Firewall with Advanced Security
- Windows OS

---

## 📋 Task Performed

### ✅ 1. Viewed Existing Firewall Rules
- Opened Windows Defender Firewall
- Navigated to Inbound Rules

### 🚫 2. Blocked Telnet (Port 23)
- Created new inbound rule
- Selected TCP
- Entered port 23
- Selected "Block the connection"
- Applied to all profiles

### ✅ 3. Allowed SSH (Port 22)
- Created new inbound rule
- Selected TCP
- Entered port 22
- Selected "Allow the connection"
- Applied to all profiles

### 🧪 4. Verified Rules
Confirmed rules were successfully applied.

### 🔄 5. Removed Test Rule
Deleted block rule for port 23 to restore original state.

---

## 📚 Key Concepts Learned
- Firewall configuration
- Inbound vs Outbound rules
- Port filtering
- TCP vs UDP
- Secure vs insecure protocols

---

## 🛡 Why Block Telnet?
Telnet (Port 23) is insecure because it transmits data in plaintext. It is vulnerable to packet sniffing and attacks.

---

## 🎯 Outcome
Successfully configured firewall rules and understood how traffic filtering works in Windows Firewall.


