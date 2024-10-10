# 🔐 ManyPassword: Your Personal Password Manager

ManyPassword is a robust, user-friendly password manager designed to keep your digital life secure and organized. Built with Ruby on Rails, it offers a seamless experience for storing, managing, and accessing your passwords safely.

## 🌟 Features

- **Secure Password Storage**: All passwords are encrypted using industry-standard algorithms
- **User-friendly Interface**: Intuitive design for effortless password management
- **Multi-device Sync**: Access your passwords across all your devices
- **Password Sharing**: Share passwords with your team securely


## 🚀 Getting Started

### Prerequisites

- Ruby 3.3.0 or higher
- Rails 7.0.0 or higher
- PostgreSQL
- TailwindCSS

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/stevenpy/many_passwords
   cd many_passwords
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Set up the database:
   ```
   rails db:create db:migrate
   ```

4. Start the server:
   ```
   bin/dev
   ```

5. Visit `http://localhost:3000` in your browser to access ManyPassword.

## 🛠️ Configuration

- Set up your environment variables in `.env` file (use `.env.example` as a template)
- Configure your mail server in `config/environments/production.rb` for password reset functionality
