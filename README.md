import React from 'react';

function HomePage() {
  return (
    <div>
      <h1>Welcome to My Facebook Landing Page</h1>
      <p>This is a landing page built with Next.js and Vercel.</p>
    </div>
  );
}

export default HomePage;
const styles = {
    container: {
      display: 'flex',
      flexDirection: 'column',
      alignItems: 'center',
      justifyContent: 'center',
      height: '100vh',
      backgroundColor: '#f0f0f0',
      fontFamily: 'Arial, sans-serif',
    },
    heading: {
      color: '#333',
    },
    paragraph: {
      color: '#666',
      textAlign: 'center',
      margin: '20px 0',
    },
  };
  
  function HomePage() {
    return (
      <div style={styles.container}>
        <h1 style={styles.heading}>Welcome to My Facebook Landing Page</h1>
        <p style={styles.paragraph}>This is a landing page built with Next.js and Vercel.</p>
      </div>
    );
  }
  
  export default HomePage;
  
    
