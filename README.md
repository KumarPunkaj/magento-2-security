# Magento 2 Security by Mageplaza

Security issues for Magento have left a big question mark in the community of online stores. This problem is specially cared when Magento-based stores which own critical information and huge transactional volume can easily become ideal prey for blackhat hackers to attack. To help online stores prevent brutal break-ins, Mageplaza has developed the Security extension.

**Magento 2 Security extension** gives store owners the ability to detect the IP addresses that are intentionally attacking their store at any given time. Therefore, they have timely measures to prevent this issue such as blocking those IP addresses or sending warning emails to store owners.

[![Latest Stable Version](https://poser.pugx.org/mageplaza/module-security/v/stable)](https://packagist.org/packages/mageplaza/module-security)
[![Total Downloads](https://poser.pugx.org/mageplaza/module-security/downloads)](https://packagist.org/packages/mageplaza/module-security)

## 1. Documentation

- Installation guide: https://www.mageplaza.com/install-magento-2-extension/
- User guide: https://www.mageplaza.com/magento-2-security/user-guide.html
- Download from our Live site: https://www.mageplaza.com/magento-2-security/
- Contribute on Github: https://github.com/mageplaza/magento-2-security
- Get Support: https://github.com/mageplaza/magento-2-security/issues

## 2. FAQs

#### Q: I got error: `Mageplaza_Core has been already defined`
A: Read solution: https://github.com/mageplaza/module-core/issues/3


## 3. How to install Security Extension

### Install via composer (recommend)

Run the following command in Magento 2 root folder:

```
composer require mageplaza/module-security
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy
```

## 4. Contribute to this module

Feel free to **Fork** and contrinute to this module and create a pull request so we will merge your changes to `master` branch.

Thanks [the contributors](https://github.com/mageplaza/magento-2-security/graphs/contributors)

--------
## 5. SWEET MAGEPLAZA EXTENSIONS TO BRING YOU MORE MONEY

### [✓ One Step Checkout](https://www.mageplaza.com/magento-2-one-step-checkout-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ ↑30% INCREASE CONVERSION RATE 

☞ ↓66% DECREASE ABANDONMENT CART

☞ ↓80% REDUCE CHECKOUT TIME

### [✓ Layered Navigation](https://www.mageplaza.com/magento-2-layered-navigation-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ ↑84% USER'S FILTERING EXPERIENCE

☞ ↑25% CONVERSION RATE

☞ ↓67% SHOPPING TIME

### [✓ Frequently Bought Together](https://www.mageplaza.com/magento-2-frequently-bought-together/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Amazon Product Recommendation Solution
 
☞ AJAX loading for better performance

☞ Support Custom Options and all product types


### [✓ Gift Card](https://www.mageplaza.com/magento-2-gift-card-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Physical, virtual or combined gift cards
 
☞ Different gift card values from prices

☞ Send cards via email, SMS, post office or messenger


### [✓ Who Bought This Also Bought](https://www.mageplaza.com/magento-2-who-bought-this-also-bought/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Display on Product Page, Category Page, Shopping Cart page

☞ AJAX loading for better performance.

☞ Flexible layout and design.


### [✓ Social Login](https://www.mageplaza.com/magento-2-social-login-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Increase signup rate up-to 30%

☞ Supports 11 Types: Facebook, Google Plus, Twitter, Linkedin, Instagram, Yahoo, Github, Foursquare, VK, Live, Amazon

☞ Easy custom design fit with your store design

☞ [Social Login on Github](https://github.com/mageplaza/magento-2-social-login)


### [✓ Shop By Brand](https://www.mageplaza.com/magento-2-shop-by-brand/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Fully Compatible with Layered Navigation

☞ Instant Search brands

☞ Import brands


### [✓ Affiliate](https://www.mageplaza.com/magento-2-affiliate-extension/?utm_source=github.com&utm_medium=link&utm_campaign=related-extension)

☞ Multiple Affiliate Campaigns

☞ Smart Referral Links

☞ Affiliate Report


## 6. Introduction
### Highlight features
It’s a minor unnoticed fact that Magento 2 doesn’t limit any number of login attempts for vague reasons behind, why this potential danger has not been considered seriously? Displaying frontend, customer knowledge, sale figures and precious transaction database are recorded in the backend thoroughly. For that reason, it’s obvious logic that hackers will try their hard to impact brutal damages to your login in the backend. Consequently, your website can be bullied continuously by many computers at the same time, by any Badguy™ groups silently, in such vulnerable time you don’t notice.

Mageplaza Security extension comes up with various choices to let you have any idea how to massive protect your store firmly. You will be right the second such nonsense endeavors is entering your internal backend.

At the level of a free module, you can explore some fundamental yet indispensable configurations within this lightweight size that you should consider installing it to your store as soon as possible.
 
#### Failed login attempt limitation
An overwhelming number of failed logins is the first sign of unwanted attack. A tool a hacker uses will try over and over again until a correct credential is entered; therefore, that would be put in danger if you don’t limit a number of trying in a certain time, to both yourself and outer enemies.

In the backend configuration, there is a field called `Maximum number of failed login attempts` that is able to restrict the above danger. According to many popular security restrictions, the ideal number of failed login attempts should be limited to be under 5 times, it’s a safe way to follow this reliable figure. Also, the other factor to determine if they’re suspicious logins or not is the amount of time those break-in attempts are taken. For example, 5 failed logins within 10 minutes are undoubtedly unusual actions that store owners have to be aware.

When you enable the module, 5 is the default number of allowed unsuccessful attempts in a 10-minute session If you have no idea how you should set up for the guarding system, you can take advantage of this default settings quickly.

#### Automatic warning emails
In Magento 2, admins have no idea when the security wall was being reached. To remedy this passive situation, this module is well integrated with the email engine. The exact helpful point in this function is, all recorded failed logins will be sent over to your email address automatically. 

In the warning email, you can check out details in the abusive IP address as well as his login time. 

#### Blacklist/Whitelist IP
Blacklist/Whitelist field is crafted and put in the configuration conveniently. 

In the Blacklist field, in order to prevent strange IP addresses from abusing your backend login page, you can list those IPs in this field (multiple IPs or multiple IP ranges at a time). Now store admin can feel peace of mind, those blocked address cannot take further process to your store anymore.

Holding the reserved meaning, Whitelist field is for entering allowed IP addresses detecting which are safety authentications from your team or colleagues.

#### Login Logs
In case you’re running a store which is managed by several administrators, this tab will be definitely an ideal interface to summary all taken place under logged details. For each of a particular login, you can figure out its ID, Time, User name, IP, Browser Agent, Url and Status (Failed or Successful).

#### Checklist
Another additional function sticked on this module is the security checklist in the backend. The checklist technique will scan your internal gears generally and give some outlines that can be deemed to be a possible security issue. From this trait you can have timely solution to remedy the problem thanks to this convenient suggestions.

### Full feature list
* Able to enable/disable Security module
* Automatic warning email
* Restrict the number of failed login attempts
* Restrict the time session of failed login attempts
* Default settings for failed login attempts and allowed duration
* Blacklist(s) IP to block IP address(es)
* Whitelist(s) IP to allow IP address(es)
* Able to apply actions to an IP, multiple IPs or range of IP address.
* Login logs with login detail (ID, Time, User name, IP, Browser Agent, Url and Status)
* The most 5 recent logins at the Dashboard
* Security checklist
* The last time login of a particular admin.
* Action log details
* File changed reports


## 7. User Guide


### How to use
You can review login records from the dashboard when entering the backend. The log displays the newest 5 logins and you can click on the login name to view the details.

![i6](https://i.imgur.com/X4qv87Y.png)

### How to configure
After logging in Magento backend, go to ``Mageplaza > Security``. We will provide detail guides to these bellow configuration
* Login Log
* Configuration

![i1](https://i.imgur.com/fQKLIhJ.png)

#### I. Configuration
##### 1.1. Brute Force Protection configuration.
Follow ``Mageplaza > Security > Configuration > General > Brute Force Protection``

![i2](https://i.imgur.com/bQfkFMl.png)

* In the **Enable** field: Choose “Yes” to turn the module on.
* In the **Send warning emails to** field: 
  * Enter the email address to be able to receive warning emails.
  * You can fill multiple emails separated with commas ``,``
* In the **Maximum number of failed login attempts** field:
  * Enter an allowable number of failed logins.
  * Default number of maximum failed login attempts is ``5`` when you enable Security module.
  * If you leave it blank or enter 0, after a failed login happens, an email will be sent.
* In the **Allowed Duration** field:
  * Enter the number of minute(s) which presents the length of a session. During this session, If the **Maximum number of failed login attempts** is reached, warning emails will be sent.
  * Default number of allowed duration is ``10`` minutes when you enable Security module.
  * If you leave the field blank or enter 0, no warning emails will be sent even if the maximum number of acceptable logins is reached.
* In the **Email Template** field: 
  * Choose the template for the warning email.
  * You can edit/customize one at ``Marketing > Email Template``.

Here’s an example of a warning emails:

![i7](https://i.imgur.com/Up4mBKw.png)

##### 1.2. Blacklist/Whitelist IPs

![i3](https://i.imgur.com/CI5lmut.jpg)

* In the **Blacklist(s)** field:
  *  All IP addresses filled in this section will be blocked whenever accessing the admin login page.
  * You are able to block one IP address, multiple IP addresses, an IP address range or multiple IP address ranges.  IP addresses are separated with commas ``,``.
  * You can also block IP addresses as wildcard masks as below:
    * ``10.0.0. *``
    * ``10.0. *. *``
    * ``10.0.0. * - 123.0.0. *``
    * ``12.3. *. * - 222.0. *. *``
 * The mark ``*`` is in the `0 - 255` range.*
* In the **Whitelist(s)** field:
  * All IP addresses that are filled in this section will be allowed whenever accessing the admin login page.
  * You can allow one IP address, multiple IP addresses, an IP address range or multiple IP address ranges.  IP addresses are separated with commas ``,``.
  *  You can also allow IP addresses as wildcard masks as these follows:
    * ``10.0.0. *``
    * ``10.0. *. *``
    * ``10.0.0. * - 123.0.0. *``
    * ``12.3. *. * - 222.0. *. *``
 * The mark ``*`` is in the `0 - 255` range.*

```
Blacklist(s) has higher priority than Whitelist(s) which means if a IP address is in the Blacklist, it will be blocked even it's in the Whitelist as well. So please make sure that you've added your IP address in the Whitelist only. 
```

#### II. Login Log
From the admin panel, make your way to ``Mageplaza > Security > Login Log``. All logins and login attempts will be recorded here.

![i4](https://i.imgur.com/AogyfB4.png)

Click ``View`` to see login details. Here’s an example:

![i5](https://i.imgur.com/1iYlCm1.png)

#### Reset Command line

* If store admins mistakenly enter their IP addresses in the Blacklist, this following command lines can be run first: 
```
bin/magento security:reset blacklist 
```
Next, run this command line:
```
bin/magento cache:flush
```
*  After you have finished running those above command lines which reset the **Blacklist(s)** field, you will be able to access the admin page again. Note that the **Blacklist(s)** field is reset now so don’t forget to reenter the blacklist IPs.
* Similarly, the **Whitelist(s)** can be reset using these command lines: 
```
bin/magento security:reset whitelist
bin/magento cache:flush
```
* If you run the command ``bin/magento security:reset``, both **Blacklist(s)** and **Whitelist(s)** will be reset.
