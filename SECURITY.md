See [https://github.com/open-policy-agent/opa/blob/main/SECURITY.md](https://github.com/open-policy-agent/opa/blob/main/SECURITY.md)

the Software Composition Analysis (SCA) scan resulted in high severity vulnerability related to npm compoenent  npm://semver:3.5.1 

suggested fix using semver version later than  4.3.2
The semver package before 4.3.2 for Node.js allows attackers to cause a denial of service (CPU consumption) via a long version string, aka a
"regular expression denial of service (ReDoS)."



