---
layout: default
title: Email Confirmed - BucketBook
---

<div class="confirmation-page">
  <div class="confirmation-card">
    <div class="confirmation-icon">✓</div>
    <h1>Email Confirmed</h1>
    <p>Your email has been verified successfully.</p>
    <p class="instruction">You can now return to the BucketBook app and sign in.</p>
  </div>
</div>

<style>
.confirmation-page {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 60vh;
  padding: 2rem;
}

.confirmation-card {
  background: var(--bg-card);
  border: 1px solid var(--border);
  border-radius: 16px;
  padding: 3rem;
  text-align: center;
  max-width: 400px;
}

.confirmation-icon {
  width: 80px;
  height: 80px;
  background: var(--success);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 40px;
  color: white;
  margin: 0 auto 1.5rem;
}

.confirmation-card h1 {
  font-size: 1.75rem;
  margin-bottom: 0.75rem;
  color: var(--text-primary);
  border: none;
  padding: 0;
}

.confirmation-card p {
  color: var(--text-secondary);
  margin-bottom: 0.5rem;
}

.confirmation-card .instruction {
  color: var(--text-muted);
  font-size: 0.95rem;
  margin-top: 1rem;
}
</style>
