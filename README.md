🛡️ Pi-Liste-Local (Kids Protection & AdBlock)

A private collection of filters for Pi-hole and AdGuard Home, designed to secure social media and YouTube for children while reducing intrusive advertisements.
📋 List Overview

    kidds-youtube.txt: Specific URLs and domains to manage or restrict YouTube access for kids.

    kidds-social-media-regex.txt: Flexible Regex filters used to block various social media platforms efficiently.

    youtube-adds.txt: A list focused on reducing YouTube ad domains (Note: DNS blocking has technical limits with YouTube video ads).

💡 Pro Tip: Use Groups for Selective Filtering

To avoid blocking social media for everyone in your household, it is highly recommended to use the Group Management feature in Pi-hole or AdGuard Home.

    Pi-hole: Create a specific "Kids" group under Group Management. Assign these lists to that group and then move your children's devices (Clients) into it.

    AdGuard Home: Use Client Settings to assign these specific filters only to your kids' tablets, consoles, or smartphones.

    Benefit: This allows adults to use social media normally while the specific devices for children remain protected.

🚀 Setup Instructions
For AdGuard Home Users

    Navigate to Filters -> DNS Blocklists.

    Click Add Blocklist -> Add a custom list.

    Copy and paste the Raw URL from this GitHub repository.

    Apply the list to specific clients in the Client Settings menu.

For Pi-hole Users

    Add the Raw URL of the desired list under Adlists.

    Important for Regex: For kidds-social-media-regex.txt, it is often better to copy the content directly into Domains -> RegEx Filter.

    Go to Group Management to ensure the lists are only active for the designated "Kids" group.

🛠 Maintenance

This is a private repository updated as needed.

    Last Updated: February 2026

    License: Unlicense (Public Domain)
