# Bienenkorb Standard theme für Magento2

## Emailthemes

| Template                   | Location                                                |
| -------------------------- | ------------------------------------------------------- |
| Header                     | Magento_Email/email/header.html                         |
| Footer                     | Magento_Email/email/footer.html                         |
| Neuer Account              | Magento_Customer/email/account_new.html                 |
| Account bestätigen         | Magento_Customer/email/account_new_confirmation.html    |
| Account bestätigt          | Magento_Customer/email/account_new_confirmed.html       |
| Account ohne passwort      | Magento_Customer/email/account_new_no_password.html     |
| Passwort reset             | Magento_Customer/email/password_reset.html              |
| Passwort reset bestätigung | Magento_Customer/email/password_reset_confirmation.html |
| Passwort neu               | Magento_Customer/email/password_new.html                |

Magento2 email templates overview:
https://docs.magento.com/m2/ee/user_guide/marketing/email-template-list.html

## Static pages

Die Statischen Seiten wurden angelegt unter `Bk24/standard/Magento_Theme/templates/`
Sie beginnen alle mit dem Prefix `bk_*`
Addressiert werden sie via
`{{block class="Magento\Framework\View\Element\Template" template="Magento_Theme::bkagb.phtml"}}`
