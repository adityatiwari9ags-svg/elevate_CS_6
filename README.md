# Password Strength Analysis

## Objective
The goal of this project is to understand what makes a password strong and to evaluate multiple passwords using online password strength tools. This helps in identifying best practices for creating secure passwords and understanding common attacks on weak passwords.

## Tools Used
- [PasswordMeter](https://www.passwordmeter.com/)  
- Any other free online password strength checkers

## Passwords Created
| Password | Description | Components |
|----------|-------------|------------|
| `password123` | Simple, common password | Lowercase + numbers |
| `PaSs1234` | Slightly more complex | Uppercase + lowercase + numbers |
| `P@ssw0rd!` | Complex | Uppercase + lowercase + numbers + symbols |
| `7r0ubL3#Secur3!` | Very strong | Uppercase + lowercase + numbers + symbols + long length |
| `123456` | Weak, common | Numbers only |

## Password Strength Results
| Password | Complexity | Score (%) | Feedback |
|----------|------------|-----------|---------|
| `password123` | Good | 43% | Simple and predictable; easy to guess |
| `PaSs1234` | Strong | 74% | Mixed case and numbers improve strength |
| `P@ssw0rd!` | Strong | 72% | Includes symbols and numbers; reasonably secure |
| `7r0ubL3#Secur3!` | Very Strong | 100% | Long, complex, highly secure |
| `123456` | Too Weak | 4% | Extremely common; very easy to crack |

## Best Practices for Creating Strong Passwords
- Use a mix of uppercase, lowercase, numbers, and symbols.  
- Make passwords at least 12–16 characters long.  
- Avoid common words, sequential numbers, or predictable patterns.  
- Use unique passwords for every account.  
- Consider passphrases (multiple unrelated words).  
- Regularly update passwords.  
- Use a reputable password manager.  
- Enable multi-factor authentication (MFA) wherever possible.

## Tips Learned from Evaluation
- Longer passwords are significantly harder to crack.  
- Complexity alone isn’t enough; unpredictability is key.  
- Avoid reusing passwords across accounts.  
- Passphrases improve both security and memorability.  
- Tools like password checkers can help gauge password strength.  
- MFA provides an additional layer of security beyond passwords.  

## Common Password Attacks
- **Brute Force:** Tries every possible combination; mitigated by long passwords and MFA.  
- **Dictionary Attack:** Uses common words/passwords; mitigated by avoiding predictable words.  
- **Credential Stuffing:** Uses leaked credentials from other breaches; mitigated by unique passwords and MFA.  
- **Rainbow Table:** Precomputed hash tables; mitigated by salting and using strong hashing algorithms like bcrypt or Argon2.  
- **Phishing:** Tricks users into revealing passwords; mitigated by MFA and user education.  

## Conclusion
Password strength is crucial for security. Strong passwords with sufficient length, complexity, and unpredictability provide robust protection against brute-force, dictionary, rainbow table, and credential-stuffing attacks. Following best practices, using password managers, and enabling MFA can greatly enhance account security.
