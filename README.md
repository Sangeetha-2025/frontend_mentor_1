# frontend_mentor_1







  /* Mobile styles (default) */
  @media (max-width: 375px) {
    .header {
      font-size: 18px;
    }
  
    .container {
      padding: 10px;
    }
  
    /* Additional mobile-specific styles */
    .navigation {
      display: flex;
      flex-direction: column;
    }
  }
  
  /* Desktop styles */
  @media (min-width: 1440px) {
    .header {
      font-size: 28px;
    }
  
    .container {
      max-width: 1400px;
      margin: 0 auto;
      padding: 40px;
    }
  
    .navigation {
      display: flex;
      flex-direction: row;
      justify-content: space-around;
    }
  }
  