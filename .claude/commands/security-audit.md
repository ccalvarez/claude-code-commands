# security-audit
You are given the following context:
$ARGUMENTS

Perform a comprehensive security audit of the provided code.

**Security Checklist:**

**1. Input Validation**
- SQL injection vulnerabilities
- XSS (Cross-Site Scripting) prevention
- Command injection risks
- File upload security
- Input sanitization completeness

**2. Authentication & Authorization**
- Password security practices
- Session management
- JWT token handling
- Access control implementation
- Privilege escalation risks

**3. Data Protection**
- Sensitive data exposure
- Encryption implementation
- Data transmission security
- PII (Personal Identifiable Information) handling

**4. Infrastructure Security**
- Environment variable usage
- API key exposure
- CORS configuration
- HTTPS implementation
- Security headers

**5. Business Logic**
- Race condition vulnerabilities
- Logic flaws
- Rate limiting implementation
- Error message information leakage

**Output Format:**
- Risk level (Critical/High/Medium/Low)
- Specific vulnerability location
- Exploitation method
- Remediation steps
- Code examples for fixes

Generate a prioritized TODO list for security improvements.