# Source Map

Use this map when the domain is unfamiliar, the user's terminology is incomplete, or no obvious official ecosystem exists. Select only the routes relevant to the task.

## Separate Discovery from Evidence

Use directories, rankings, curated lists, and community sites to discover names and terminology. Do not use their ranking as proof of quality.

Base the decision on primary sources: official documentation, specifications, source repositories, release notes, license text, security advisories, and maintainer statements.

## Source Routes

| Need | Start with | Verify with |
| --- | --- | --- |
| Open-source implementations | [GitHub Topics and code search](https://github.com/topics), [GitLab Explore](https://gitlab.com/explore), [Codeberg Explore](https://codeberg.org/explore/repos) | Repository releases, issues, contributors, license, and security policy |
| Ecosystem packages | The repository's package manager and registry: [npm](https://www.npmjs.com/), [PyPI](https://pypi.org/), [crates.io](https://crates.io/), [Maven Central](https://central.sonatype.com/), [NuGet](https://www.nuget.org/), [pkg.go.dev](https://pkg.go.dev/), [RubyGems](https://rubygems.org/), [Packagist](https://packagist.org/), or [Swift Package Index](https://swiftpackageindex.com/) | Official package docs, source repository, provenance, supported versions, and changelog |
| Dependency health | [deps.dev](https://deps.dev/), [OSV](https://osv.dev/), [OpenSSF Scorecard](https://scorecard.dev/), [GitHub Advisory Database](https://github.com/advisories) | Exact selected version, transitive dependency graph, unresolved advisories, and project security practices |
| Web and Internet standards | [W3C](https://www.w3.org/standards/), [WHATWG](https://spec.whatwg.org/), [RFC Editor](https://www.rfc-editor.org/), [TC39 proposals](https://github.com/tc39/proposals) | Specification maturity, browser or runtime support, errata, and current status |
| Platform UI | [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines), [Material Design](https://m3.material.io/), [Microsoft Fluent](https://fluent2.microsoft.design/), [WCAG](https://www.w3.org/WAI/standards-guidelines/wcag/) | Native component documentation, accessibility requirements, and platform version support |
| Cloud and infrastructure | Official provider documentation, reference architectures, and [CNCF Landscape](https://landscape.cncf.io/) | Provider support policy, operational requirements, pricing, security, and lock-in |
| Agent capabilities | [skills.sh](https://skills.sh/), the agent vendor's official skill or plugin catalog, and official MCP integrations | Skill source, instructions, permissions, maintenance, and installation behavior |
| Research and algorithms | [Semantic Scholar](https://www.semanticscholar.org/), [arXiv](https://arxiv.org/), and [Papers with Code](https://paperswithcode.com/) | Original paper, peer-review status, authors' implementation, benchmark conditions, and license |
| Curated ecosystem maps | Relevant Awesome lists, official showcases, framework marketplaces, and template galleries | Every candidate's primary sources; curated inclusion is discovery evidence only |
| Real-world limitations | Repository issues and discussions, [Stack Overflow](https://stackoverflow.com/), maintainer forums, and focused community discussions | Reproduce the issue, check dates and versions, and confirm against current documentation |
| SaaS and hosted products | [AlternativeTo](https://alternativeto.net/), [G2](https://www.g2.com/), [Capterra](https://www.capterra.com/), and [Product Hunt](https://www.producthunt.com/) | Vendor documentation, current pricing, data ownership, export path, security attestations, and terms |

## Selection Rules

- Search the official ecosystem before using a general web query.
- Search by capability, expert terminology, protocol, file format, and platform.
- Use popularity only as a discovery signal; never as the sole acceptance criterion.
- Match package names to their official source repositories to reduce typosquatting risk.
- Inspect the actual license file. No license means no permission to copy or adapt the code.
- Check the exact version intended for use, not only the project's latest documentation.
- Prefer an official scaffold or native feature when it satisfies the hard constraints.
- Stop using a route when it produces only stale, abandoned, incompatible, or unverifiable candidates.
