**SkyShadow ✈️ 🌤️**

---

**📝 Description**

SkyShadow is your go-to Flask-based web app for a comfortable and sun-free flight experience 🌞❌. Just enter your departure and arrival cities, flight date, and time. We'll recommend the best seat to keep you in the shade 🌚.

---

**🔧 Requirements**

- **Python 3.x** 🐍
- **Flask** 🌶️
- **Docker** 🐳 (optional)

---

**🛠 Installation**

1. **📦 Clone the Repository**

    ```bash
    git clone https://github.com/NikGor/SkyShadow.git
    ```

2. **📍 Navigate to Project Directory**

    ```bash
    cd SkyShadow
    ```

3. **🔗 Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

---

**🚀 Usage**

***🖥️ Local Launch***

```bash
flask run
```

***🐳 Docker Launch***

```bash
docker build -t skyshadow .
docker run -p 5000:5000 skyshadow
```

Then, open your browser and go to [http://localhost:5000](http://localhost:5000). Fill out the required fields, and we’ll point you to the sun-free side of the plane 🌗.

---

**🔒 License**

This project is under the MIT License. Check out the [LICENSE.md](LICENSE.md) file for more details 📄.