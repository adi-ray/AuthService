# 🔐 Auth Service

This microservice is responsible for handling **authentication** and **authorization** within the system.

---

## ✅ What is Authentication?

Authentication is the process of **verifying a user's identity**. The general singup/login/logout flow is used to authenticate a user.  
It answers the question:  
**"Who is the user?"**

## 🔓 What is Authorization?

Authorization determines **what actions a user is allowed to perform** after they have been authenticated.  
It answers the question:  
**"What can the user do?"**

---

## 🔑 Authentication Methods

1. **Mobile Number-Based Authentication**

   - Can be implemented using **OTP verification**.
   - See [MDN Web OTP API Documentation](https://developer.mozilla.org/en-US/docs/Web/API/WebOTP_API) for more details.

2. **OAuth Integration**

   - Authenticate users via third-party platforms such as:
     - **Google**
     - **GitHub**
   - This approach reduces friction by using existing accounts.

3. **Token-Based Authentication**
   - Uses **JWT (JSON Web Token)**.
   - JWTs are generated using **client credentials** and sent with requests to authenticate and authorize users securely.
