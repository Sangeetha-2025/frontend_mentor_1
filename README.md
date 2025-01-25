* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background-color: hsl(0, 0%, 8%);
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

.container {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    height: 500px;
    width: 300px;
    background-color: hsl(0, 0%, 20%);
    border-radius: 10px;
    overflow: hidden;
}

.profile-card {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

img {
    border-radius: 50%;
    width: 100px;
    height: 100px;
}

.profile-info {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
}

h1 {
    color: white;
    margin-top: 10px;
    font-size: 14px;
}

p {
    color: white;
    font-size: 12px;
}

.area {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
    color: hsl(75, 94%, 57%);
}

.social-links {
    display: block;
}

/* Mobile Styles */
@media (max-width: 375px) {
    .container {
        width: 100%;
        height: 100%;
        padding: 10px;
    }

    .profile-card {
        margin-top: 20px;
    }

    img {
        width: 80px;
        height: 80px;
    }

    h1 {
        font-size: 12px;
    }

    p {
        font-size: 10px;
    }

    .area {
        font-size: 14px;
    }
}

/* Desktop Styles */
@media (min-width: 1440px) {
    .container {
        width: 400px;
        height: 600px;
    }

    img {
        width: 120px;
        height: 120px;
    }

    h1 {
        font-size: 18px;
    }

    p {
        font-size: 16px;
    }

    .area {
        font-size: 18px;
    }
}
