function bookNow() {
    alert("✅ Turf booked successfully!");
  }
  
  /* FORM VALIDATION */
  document.getElementById("contactForm").addEventListener("submit", function(e) {
    e.preventDefault();
  
    let phone = document.getElementById("phone").value;
    let email = document.getElementById("email").value;
  
    if (!/^\d{10}$/.test(phone)) {
      alert("❌ Enter valid 10 digit phone number");
      return;
    }
  
    if (!email.includes("@")) {
      alert("❌ Enter valid email");
      return;
    }
  
    alert("✅ Message sent successfully!");
  });
  
  /* GOOGLE LOGIN */
  function googleLogin() {
    window.location.href = "https://accounts.google.com/";
  }
  
  /* SMOOTH SCROLL */
  document.querySelectorAll("nav a").forEach(link => {
    link.addEventListener("click", function(e) {
      e.preventDefault();
      document.querySelector(this.getAttribute("href"))
        .scrollIntoView({ behavior: "smooth" });
    });
  });