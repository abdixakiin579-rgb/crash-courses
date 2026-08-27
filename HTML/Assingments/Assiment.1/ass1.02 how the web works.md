# URL Breakdown & Role-Play Activity

## 1. URL Breakdown

### URL Tusaale

```text
https://www.example.com:8080/courses/web/index.html?id=25#lesson1
```

| Qaybta | Magaca | Sharaxaad |
|---|---|---|
| `https` | Protocol/Scheme | Habka browser-ku ula xiriiro server-ka |
| `www` | Subdomain | Qayb ka mid ah domain-ka |
| `example.com` | Domain | Cinwaanka website-ka |
| `:8080` | Port | Port-ka server-ku adeegga ku siinayo |
| `/courses/web/` | Path | Meesha resource-ku ku yaallo server-ka |
| `index.html` | File/Resource | Bogga browser-ku codsanayo |
| `?id=25` | Query String | Xog loo diro server-ka |
| `#lesson1` | Fragment | Qayb gaar ah oo bogga ka mid ah |

### Natiijo

URL-ku wuxuu browser-ka siinayaa tilmaamo ku saabsan **server-ka uu aadayo iyo resource-ka uu raadinayo**.

---

## 2. Role-Play: Request–Response Cycle

Kooxdu waxay qaadan kartaa 4 door:

### 👤 User

> “Waxaan rabaa inaan furo `www.example.com`.”

### 🌐 Browser

> “Waxaan u baahanahay inaan ogaado IP address-ka website-kan.”

### 📖 DNS Server

> “`www.example.com` wuxuu leeyahay IP address-ka server-ka.”

### 🖥️ Web Server

> “Waxaan helay request-ka browser-ka. Waa kan webpage-ka la codsaday.”

### 🌐 Browser

> “Waan helay webpage-ka, hadda waxaan tusayaa User-ka.”

### 👤 User

> “Webpage-kii waa ii furmay.”

---

## Request–Response Cycle

```text
User
  ↓
Browser
  ↓
DNS Server
  ↓
Web Server
  ↓
Browser
  ↓
User
```

### Ujeeddada Activity-ga

Activity-gani wuxuu ardayda ka caawinayaa inay fahmaan sida **request** loo diro iyo sida **response** dib loogu soo celiyo marka browser-ku webpage codsado.
