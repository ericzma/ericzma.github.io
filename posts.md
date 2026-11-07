---
layout: page
title: Posts
---

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date_to_string }}
{% endfor %}

## Disclaimer

All content on this site is provided for **information and reference purposes
only**, without warranty of any kind, express or implied, including but not
limited to warranties of accuracy, completeness, merchantability, or fitness
for a particular purpose.

- **No professional advice.** Nothing on this site constitutes technical,
  legal, financial, investment, or tax advice. In particular, articles about
  cryptocurrency and blockchain are *not* investment advice. Always consult a
  qualified professional before making decisions.
- **No warranty.** All content is provided "AS IS" and may contain errors,
  omissions, or become outdated. Use at your own risk.
- **No liability.** To the maximum extent permitted by law, the author shall
  not be liable for any loss or damage — direct or indirect — arising from the
  use of, or reliance on, any content on this site, including but not limited
  to data loss, system damage, financial loss, or business interruption.
- **Experiments and code.** Commands, code, and configurations published here
  can be risky (e.g., disk operations, key management, system modifications).
  Test in non-production environments first. You are solely responsible for
  any actions you take based on this content.
- **External links.** External links are provided for convenience only. The
  author is not responsible for their content and does not endorse them.
- **Trademarks and opinions.** Product names mentioned are the property of
  their respective owners. Views expressed are the author's own, not those of
  any employer or affiliated organization.
- **Republished content.** The author is not responsible for content from this
  blog republished on other blogs or websites without permission.

This disclaimer, together with the [Terms and Policy](/terms/), applies to all
pages and posts on this site. This policy is subject to change without notice.
If you have any questions, feel free to [contact me](/contact/).
