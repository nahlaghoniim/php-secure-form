# PHP Secure Registration Form

A simple and secure PHP registration form with:

- Input sanitization (`htmlspecialchars`, `stripslashes`)
- Server-side validation
- Email validation using `filter_var()`
- Username length validation (min 6, max 16 characters)
- Password + confirm password verification
- Optional CV URL validation
- Bootstrap 5 responsive UI
- Clean error handling with `is-invalid` Bootstrap styling

---

##  Features

###  Security
- Sanitizes all POST inputs with a custom `post_data()` function
- Protects against XSS
- Uses PHP validation functions for emails and URLs

###  Validation
- **Username**: required, 6–16 characters  
- **Email**: valid email format  
- **Password**: minimum 6 characters  
- **Confirm Password**: must match password  
- **CV URL (optional)**: must be a valid URL  
