# PROVA TÈCNICA
### **Proves tècniques per a administradors de sistemes i xarxes**

Aquestes proves poden prendre diferents formats: preguntes teòriques, exercicis pràctics, troubleshooting en entorns simulats o fins i tot exercicis en viu.

---

## **1. Tipus de proves tècniques**
### **A) Preguntes teòriques**
Aquestes preguntes avaluen el coneixement fonamental sobre administració de sistemes i xarxes. Exemples:

#### **Sistemes operatius (Windows/Linux)**
- Explica la diferència entre un hipervisor de tipus 1 i tipus 2.
- Quina diferència hi ha entre un servei i un procés en Linux?
- Com solucionaries un problema on un servidor té un alt consum de CPU?
- Com es gestiona l'autenticació en un servidor Linux amb PAM?
- Com configures una RAID 1 i una RAID 5 en Linux?

#### **Xarxes i protocols**
- Explica la diferència entre TCP i UDP i quan és millor usar cada protocol.
- Com solucionaries problemes de latència en una xarxa?
- Explica com funciona el protocol DHCP i quin és el seu procés de concessió d’IP.
- Quina diferència hi ha entre una VLAN i una subxarxa?
- Com configuraries un servidor DNS per tenir redundància?

#### **Seguretat i gestió d’accés**
- Com s’implementa una política de Least Privilege en un entorn Windows Server?
- Què és SELinux i com es configura?
- Com protegiries un servidor exposat a internet contra atacs DDoS?
- Com pots detectar si un servidor ha estat compromès?
- Explica com funciona un tallafocs i quina diferència hi ha entre un Stateful i un Stateless Firewall.

---

### **B) Proves pràctiques**
Aquestes proves avaluen la capacitat de posar en pràctica els coneixements en entorns reals o simulats.

#### **1. Troubleshooting de sistemes**
L’entrevistador pot donar un escenari amb un problema en un sistema i demanar al candidat que el resolgui. Exemples:
- "Tens un servidor Linux que de sobte deixa de respondre. Quins passos faries per diagnosticar el problema?"
- "Els usuaris d'un domini de Windows no poden iniciar sessió, com diagnosticaries la causa?"
- "Un servidor de base de dades MySQL està funcionant lentament. Com ho optimitzaries?"

#### **2. Configuració de serveis**
Poden demanar que configuris serveis essencials, com:
- Configurar un servidor web amb Apache/Nginx i verificar que funcioni correctament.
- Configurar un servidor SSH amb autenticació basada en clau pública i restringir l’accés per IP.
- Instal·lar i configurar un servidor DHCP i verificar que assigna IPs correctament.
- Configurar un tallafocs amb `iptables` o `firewalld` en Linux.

#### **3. Eines de xarxes i diagnòstic**
Poden fer proves en què hagis d’utilitzar eines de diagnòstic:
- Capturar i analitzar trànsit de xarxa amb `Wireshark` o `tcpdump`.
- Utilitzar `ping`, `traceroute` i `netstat` per identificar problemes de xarxa.
- Diagnosticar problemes d’autenticació amb `ldapsearch` en un entorn Active Directory.

#### **4. Automatització i scripting**
Moltes empreses esperen que un administrador de sistemes pugui automatitzar tasques. Les proves poden incloure:
- Escriure un script en Bash o Python per monitoritzar l'ús de CPU i memòria d’un servidor.
- Configurar un playbook d’Ansible per desplegar una aplicació en múltiples servidors.
- Escriure un script per crear i gestionar usuaris en Linux.

#### **5. Virtualització i Cloud**
Si el rol inclou virtualització o gestió en el núvol, poden fer proves com:
- Configurar una màquina virtual en VMware o VirtualBox.
- Crear una instància a AWS/Azure i configurar-la amb seguretat.
- Escriure una política de seguretat a Terraform per provisionar infraestructura.

---

### **C) Proves en viu**
Algunes empreses fan **entrevistes tècniques en viu**, on es demana al candidat que executi accions en una màquina virtual o simulació. Exemples:
- Accedir a un servidor via SSH i configurar usuaris amb permisos específics.
- Crear i muntar un sistema RAID en Linux.
- Configurar una VPN en un entorn empresarial.
- Resoldre un problema de retard en la resposta d’un servidor web.

