When designing a new application, creating a secure architecture prevents vulnerabilities before they even become part of the application. This prevents costly repairs and repudiation problems.

Refer to proactive control [C4: Address Security form the Start][control4] and its [cheatsheets][csproactive-c1]
for more context from the OWASP Top 10 Proactive Controls project,
and use the lists below as suggestions for a checklist that has been tailored for the individual project.

#### 3. File management

1. Do not pass user supplied data directly to any dynamic include function
2. Require authentication before allowing a file to be uploaded
3. Limit the type of files that can be uploaded to only those types that are needed for business purposes
4. Validate uploaded files are the expected type by checking file headers rather than by file extension
5. Do not save files in the same web context as the application
6. Prevent or restrict the uploading of any file that may be interpreted by the web server.
7. Turn off execution privileges on file upload directories
8. When referencing existing files, use an allow-list of allowed file names and types
9. Do not pass user supplied data into a dynamic redirect
10. Do not pass directory or file paths, use index values mapped to pre-defined list of paths
11. Never send the absolute file path to the client
12. Ensure application files and resources are read-only
13. Scan user uploaded files for viruses and malware

#### References

* OWASP [Application Security Verification Standard][asvs] (ASVS)
* OWASP [Mobile Application Security][mas]
* OWASP [Top 10 Proactive Controls][proactive10]

----

The OWASP Developer Guide is a community effort; if there is something that needs changing
then [submit an issue][issue060201] or [edit on GitHub][edit060201].

[asvs]: https://owasp.org/www-project-application-security-verification-standard/
[csproactive-c1]: https://cheatsheetseries.owasp.org/IndexProactiveControls.html#c1-define-security-requirements
[control4]: https://top10proactive.owasp.org/the-top-10/c4-secure-architecture/
[edit060201]: https://github.com/OWASP/DevGuide/blob/main/docs/en/04-design/02-web-app-checklist/01-define-security-requirements.md
[issue060201]: https://github.com/OWASP/DevGuide/issues/new?labels=enhancement&template=request.md&title=Update:%2004-design/02-web-app-checklist/01-define-security-requirements
[mas]: https://mas.owasp.org/
[proactive10]: https://top10proactive.owasp.org/
