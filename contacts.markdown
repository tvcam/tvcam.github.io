---
layout: default
title: Contact Me
description: Get in touch with Vibol T., Ruby on Rails full-stack developer. Fill out the form to discuss your project, legacy code rescue, API integrations, or infrastructure needs.
---

<style>
.contact-hero {
  text-align: center;
  margin-bottom: 2rem;
  padding: 1.5rem;
  background-color: #f8f9fa;
  border-radius: 8px;
}

.contact-hero h2 {
  margin-top: 0;
  color: #333;
}

.contact-hero p {
  color: #666;
  font-size: 1rem;
  margin-bottom: 0;
}

.contact-form {
  max-width: 600px;
  margin: 0 auto;
  padding: 2rem;
  background: #fff;
  border: 1px solid #e1e4e8;
  border-radius: 6px;
}

.contact-form .form-group {
  margin-bottom: 1.5rem;
}

.contact-form label {
  display: block;
  margin-bottom: 0.5rem;
  font-weight: 600;
  color: #24292e;
  font-size: 0.95rem;
}

.contact-form input[type="text"],
.contact-form input[type="email"],
.contact-form select,
.contact-form textarea {
  width: 100%;
  padding: 0.75rem;
  font-size: 1rem;
  line-height: 1.5;
  color: #24292e;
  background-color: #fff;
  border: 1px solid #d1d5db;
  border-radius: 6px;
  transition: border-color 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  box-sizing: border-box;
}

.contact-form input[type="text"]:focus,
.contact-form input[type="email"]:focus,
.contact-form select:focus,
.contact-form textarea:focus {
  outline: none;
  border-color: #0366d6;
  box-shadow: 0 0 0 3px rgba(3, 102, 214, 0.1);
}

.contact-form textarea {
  min-height: 120px;
  resize: vertical;
}

.contact-form .form-note {
  font-size: 0.875rem;
  color: #6a737d;
  margin-top: 0.25rem;
}

.contact-form button[type="submit"] {
  display: inline-block;
  padding: 0.75rem 1.5rem;
  font-size: 1rem;
  font-weight: 600;
  line-height: 1.5;
  color: #fff;
  background-color: #0366d6;
  border: 1px solid #0366d6;
  border-radius: 6px;
  cursor: pointer;
  text-decoration: none;
  transition: background-color 0.2s ease-in-out, border-color 0.2s ease-in-out;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  width: 100%;
}

.contact-form button[type="submit"]:hover {
  background-color: #0256cc;
  border-color: #0256cc;
}

.contact-form button[type="submit"]:active {
  background-color: #0249b3;
  border-color: #0249b3;
}

.privacy-note {
  margin-top: 1.5rem;
  padding: 1rem;
  background-color: #f6f8fa;
  border-left: 3px solid #0366d6;
  border-radius: 3px;
  font-size: 0.875rem;
  color: #586069;
}

.privacy-note strong {
  color: #24292e;
}

@media (max-width: 768px) {
  .contact-form {
    padding: 1.5rem;
    margin: 0 1rem;
  }
  
  .contact-hero {
    margin: 0 1rem 2rem 1rem;
    padding: 1rem;
  }
}
</style>

<div class="contact-hero">
  <h2>Let's Discuss Your Project</h2>
  <p>Fill out the form below and I'll get back to you within 24 hours. Whether you need legacy code rescue, API integrations, or a new application built, I'm here to help.</p>
</div>

<form class="contact-form" action="https://formspree.io/f/xkgnwjrv" method="POST">
  <div class="form-group">
    <label for="name">Your Name *</label>
    <input type="text" id="name" name="name" placeholder="John Doe" required>
  </div>

  <div class="form-group">
    <label for="email">Your Email *</label>
    <input type="email" id="email" name="email" placeholder="john@example.com" required>
  </div>

  <div class="form-group">
    <label for="project_type">Project Type *</label>
    <select id="project_type" name="project_type" required>
      <option value="">Select a project type...</option>
      <option value="new_development">New Development</option>
      <option value="legacy_rescue">Legacy Code Rescue / Modernization</option>
      <option value="api_integration">API Integration</option>
      <option value="infrastructure">Infrastructure / DevOps</option>
      <option value="ecommerce">E-commerce Integration</option>
      <option value="consulting">Technical Consulting</option>
      <option value="other">Other</option>
    </select>
  </div>

  <div class="form-group">
    <label for="timeline">Timeline *</label>
    <select id="timeline" name="timeline" required>
      <option value="">Select timeline...</option>
      <option value="asap">ASAP / Urgent</option>
      <option value="1_3_months">1-3 months</option>
      <option value="3_6_months">3-6 months</option>
      <option value="exploring">Just exploring / No rush</option>
    </select>
  </div>

  <div class="form-group">
    <label for="budget">Budget Range (Optional)</label>
    <select id="budget" name="budget">
      <option value="">Select budget range...</option>
      <option value="under_5k">Under $5,000</option>
      <option value="5k_15k">$5,000 - $15,000</option>
      <option value="15k_50k">$15,000 - $50,000</option>
      <option value="50k_plus">$50,000+</option>
      <option value="discuss">Prefer to discuss</option>
    </select>
    <span class="form-note">This helps me provide a more accurate estimate</span>
  </div>

  <div class="form-group">
    <label for="message">Your Message *</label>
    <textarea id="message" name="message" placeholder="Tell me about your project, what you're trying to achieve, and any specific challenges you're facing..." required></textarea>
  </div>

  <button type="submit">Send Message</button>

  <div class="privacy-note">
    <strong>🔒 Your information is secure</strong><br>
    Your details will only be used to respond to your inquiry. I never share your information with third parties.
  </div>
</form>
