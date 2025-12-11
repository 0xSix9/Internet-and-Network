# Internet-Network
# Fundamental Internet & Web Concepts Every Developer Must Know
![Internet](https://github.com/0xSix9/Internet-and-Network/blob/c6cc52c43d232ceb1c0df723ce8248c07ef7ac93/img/1.png)
### What is the Internet?
The Internet is the largest network ever created by humans — a huge network of interconnected devices, servers, cables, and satellites.

**Simple definition: The Internet is how computers and phones talk to each other.**

When you search for something in a browser, your request travels through routers, ISPs, and servers, and the response returns in milliseconds.

The Internet is a global collection of networks that began in 1969 with four core hosts and has expanded massively since then. It belongs to no single entity.

### How does the Internet work?
Main components:

- **Devices:** phone, laptop, tablet, smart TV  
- **Modem & Router:** modem receives internet from ISP → router distributes  
- **ISP:** gateway to the internet  
- **Servers:** store and deliver information  
- **Cables & Satellites:** physical paths of the data

### What happens when you open a site?
Example: opening YouTube

1. You type `youtube.com`
2. Your device asks DNS for the IP
3. Modem sends request to ISP
4. ISP connects to nearest YouTube server
5. Server sends back the page
6. Browser displays it

---

## ISP
### What is an ISP?
ISP = **Internet Service Provider**, the company that gives you internet access and routes your requests.

### What does an ISP do?
- Connects you to the internet  
- Assigns an IP  
- Relays your requests  
- Provides DNS  
- Controls speed and quality  
- Provides hosting and email services  
- Ensures network security  

### Types of ISPs
- **Home ISPs:** ADSL, fiber, 4G/5G  
- **Web Hosting Providers:** data centers, servers, cloud  
- **Backbone ISPs:** international providers of global internet  

### Services ISPs Provide
- Internet connection  
- IP address (static or dynamic)  
- DNS  
- Routing  
- Server hosting  
- Email services  
- Network security  
- Traffic filtering  

---

## Server
### What is a Server?
A server is a computer that is **always on** and provides services to other devices (clients).

**Server = provides service**  
**Client = receives service**

### In web development, a server handles:
1. **Receiving requests** (HTTP/HTTPS)
2. **Processing logic** (backend, database)
3. **Sending responses** (HTML, CSS, JS, JSON)

---

## Hosting
### What Is Hosting?
Hosting is storage space on a server where your website’s files live so users can access the site.

### How Hosting Works
1. You have a domain  
2. Domain points to host’s IP  
3. User sends request  
4. Host sends files  
5. Browser displays site  

### Types of Hosting
#### 1. Shared Hosting
- Many sites on one server  
- Cheap, limited resources  

#### 2. VPS (Virtual Private Server)
- Virtual server  
- More control, better performance  

#### 3. Dedicated Server
- Entire server for one user  
- Expensive, powerful  

#### 4. Cloud Hosting
- Distributed across servers  
- Fast, scalable  
- AWS, Google Cloud, Azure  

#### 5. WordPress Hosting
- Optimized for WordPress  

#### 6. Managed Hosting
- Fully managed by provider  

### Hosting Plans Include:
- Storage  
- Bandwidth  
- CPU & RAM  
- Database support  
- cPanel / DirectAdmin  
- SSL  
- Email  
- Backups  

---

## Domain
### What Is a Domain?
A domain is a **human-readable name** like `google.com` that replaces numerical IP addresses.

### How Domains Work
1. User enters domain  
2. DNS converts domain → IP  
3. Browser connects to server  

### Parts of a Domain
- **Name:** example  
- **TLD:** .com, .net  

### Types of Domains
- **TLDs** (.com, .net…)  
- **Country domains** (.ir, .uk…)  
- **Subdomains** (blog.example.com)  

### Why Domains Matter?
- Easy access  
- Branding  
- Connect domain → host  

---

## IP
### What is an IP Address?
An IP is a unique numerical address assigned to every device on the internet.

### Why IP Matters
- Without IP, no connectivity  
- Browser uses IP to reach server  
- Ensures data reaches correct destination  

### Types of IP
#### IPv4
- Example: `192.168.1.1`  
- Limited capacity  

#### IPv6
- Example: `2001:db8::8a2e`  
- Huge address range  

### Public vs Private IP
- **Public:** visible on internet  
- **Private:** inside local network  

### Static vs Dynamic IP
- **Static:** fixed, good for servers  
- **Dynamic:** changes, for home users  

### How IP Works
1. User enters domain  
2. DNS finds IP  
3. Browser connects to server  
4. Site loads  

---

## DNS
### What is DNS?
**DNS = Internet’s phone book**  
It converts domain names into server IP addresses.

Example:  
`google.com → 142.250.185.14`

### What DNS Does
- Converts domain → IP  
- Caching for faster loading  
- Provides redundancy and stability  

### How DNS Works
1. User enters domain  
2. Browser asks DNS Resolver  
3. If not cached → goes to root  
4. Then TLD server (.com)  
5. Then authoritative DNS  
6. Returns IP → browser connects  

### Important DNS Records
- **A:** IPv4  
- **AAAA:** IPv6  
- **CNAME:** alias  
- **MX:** mail server  
- **TXT:** SPF, DKIM  
- **NS:** DNS servers  

### Why DNS Is Important
- Website speed  
- Security (DNSSEC)  
- Domain ↔ host connection  
- Email functionality  
- Critical internet infrastructure  

---

## HTTP & HTTPS
### What is HTTP?
**HyperText Transfer Protocol**  
Defines how browsers and servers exchange data.

**Features:**
- Simple  
- No encryption  
- Fast  
- Insecure → data readable by attackers  

### What is HTTPS?
**HyperText Transfer Protocol Secure**  
Encrypted using SSL/TLS.

**Features:**
- Data encryption  
- Server authentication  
- Protection from MITM attacks  
- Required for logins, payments  

---

## API
### What is an API?  
API = **Application Programming Interface**  
A communication bridge between applications.

### Example
A weather website receives data from a weather API.

### What APIs Do
1. Allow apps to communicate  
2. Send/receive data (JSON/XML)  
3. Prevent direct database access  
4. Power modern applications  

### Importance for Developers
- All apps use APIs  
- React/Vue/Next.js rely on APIs  
- Used for:
  - Payments  
  - Authentication  
  - Markets  
  - Social networks  
  - Blockchain  

