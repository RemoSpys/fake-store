
# Vue 3 + Vite Project Setup Guide

This guide will help you set up a Vue 3 project using Vite on Ubuntu. We'll go through updating your system, installing Node.js, npm, and project dependencies like Axios, Tailwind CSS, and Vue Router. Additionally, you'll find code blocks that are easy to copy with a single click!

---

## Prerequisites

### 1. Update Ubuntu

Update your Ubuntu system to ensure it's up-to-date:

```bash
sudo apt update && sudo apt upgrade -y
```

### 2. Install Node.js and npm

Install the latest stable version of Node.js (which comes with npm):

```bash
curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs
```

Verify that Node.js and npm are installed correctly:

```bash
node -v
npm -v
```
---

## Setting Up the Project

### 1. Clone the Repository

Clone the project repository to your local machine:

```bash
git clone git@github.com:RemoSpys/fake-store.git
cd fake-store
```

### 2. Install Project Dependencies

Install the necessary dependencies for the project:

```bash
npm install
```

### 3. Install Axios

Install Axios for handling HTTP requests:

```bash
npm install axios
```

### 4. Install and Configure Tailwind CSS

Set up Tailwind CSS by installing it along with PostCSS and Autoprefixer:

```bash
npm install -D tailwindcss postcss autoprefixer
```

### 5. Install Vue Router

Install Vue Router to handle routing in your project:

```bash
npm install vue-router@4
```

For more details, check out the official [Vue Router documentation](https://router.vuejs.org/installation.html).

---

## Running the Project

Now that everything is installed and configured, you can start the development server. Run the following command:

```bash
npm run dev
```

You should now be able to access the project at `http://localhost:5173`.
---

## Additional Resources

- [Vue 3 Documentation](https://v3.vuejs.org/)
- [Vite Documentation](https://vitejs.dev/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Vue Router Documentation](https://router.vuejs.org/)
- [Axios Documentation](https://axios-http.com/docs/intro)

---

## License

This project is licensed under the MIT License.
