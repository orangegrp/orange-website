<!-- src/routes/privacy-policy.svelte -->

<script>
export let lastUpdated = "30/12/2023";
</script>

<div>
    <main>
        <h1>Privacy Policy</h1>
        <p>Last updated: {lastUpdated}</p> 
        <p>orange🟠 by 332 ("us", "we", or "our") operates Internet services (the "Services") as follows:</p>
        <ul class="list-disc ml-8">
            <li>orange🟠 "Discord" Bot (the "Bot")</li>
            <li>orange🟠 Code Runner Service (the "CRS", "orange🟠 CRS")</li>
            <li>orange🟠 Dash (the "Dash", "dashboard", "control panel", "admin panel")</li>
        </ul>
    
        <h2>Information Collection and Use</h2>
        <p>
            We may collect information about you, your device and your use of the Services. The type of information collected and the purposes
            for which we collect it may differ between Services.
        </p> 

        <h3>When you use the Bot, we may collect and store the following data:</h3>
        <ul class="list-disc ml-8">
            <li>Discord account user identifiers and public metadata (including avatar URIs, usernames, nicknames, display names, etc)</li>
            <li>Discord guild identifiers including public (and in some cases private) guild metadata (including guild name, guild icon URIs, banner image URIs, guild events, audit logs, etc)</li>
            <li>Discord text channel data (including messages, reactions, mentions, attachments, embeds, other message components, etc)</li>
        </ul>

        <h3>When you use the CRS exclusively, we may collect and store the following data:</h3>
        <ul class="list-disc ml-8">
            <li>Internet Protocol Version 4 (IPv4) Address and related port numbers</li>
            <li>Device information and metadata (operating system, browser type, browser version, etc)</li>
            <li>Inferred geolocation data (based on IP addresses and device metadata)</li>
        </ul>

        <p>
            Note, in some cases, when using the CRS, for instance when using it through the Bot, none of the above data may be collected about you.
            Instead, the collected data would relate to the running Bot instance offering the CRS through the Discord platform.
        </p>

        <h2>Use of Data</h2>
        <p>We use the collected data for the following purposes:</p> 
        <ul class="list-disc ml-8">
            <li>Providing and maintaining the Services</li>
            <li>Improving the Services</li>
            <li>Monitoring the usage of the Services for research and development purposes</li>
            <li>Detecting and preventing abuse of the Services</li>
            <li>Protecting our infrastructure and Services from cyber security threats</li>
            <li>Responding to cyber security threats</li>
            <li>Regulatory compliance and law enforcement purposes</li>
        </ul>

        <h2>Sharing of Data</h2>
        <p>orange🟠 does not sell your data to third parties. We may share your data with a limited number of upstream service providers in order for us
            to be able to deliver the Services. These third parties may include:
        </p> 
        <ul class="list-disc ml-8">
            <li>Alphabet Inc.</li>
            <li>Amazon.com, Inc.</li>
            <li>Amazon Web Services, Inc.</li>
            <li>Apple Inc.</li>
            <li>Cloudflare Inc.</li>
            <li>DigitalOcean Holdings Inc.</li>
            <li>Discord Inc.</li>
            <li>GitHub Inc.</li>
            <li>Meta Platforms Inc.</li>
            <li>Microsoft Corporation</li>
            <li>OpenAI Ireland Ltd</li>
            <li>OpenAI, L.L.C</li>
            <li>opencve.io</li>
            <li>Oracle Corporation</li>   
            <li>shodan.io</li>         
            <li>Vercel Inc.</li>      
        </ul>

        <div class="inline-block p-2 pl-3 pr-3 border border-orange-950 rounded-lg card mb-6">
            <p class="text-xs k-light">
                Your data is only ever transmitted to these providers if you give express consent or imply it through your use of a Service
                that strictly requires an upstream provider. orange🟠 will never transmit data to third parties without your consent and will
                develop the Services in a privacy respecting way at all times.
            </p>	
        </div>	

        <h2>Cookies</h2>  
        <p>Cookies are files with a small amount of data, which may include an anonymous unique identifier. 
           Cookies are sent to your browser from a website and stored on your computer's hard drive. 
           We use cookies to "remember" your login session on the Dash and for analytics purposes using a self-hosted analytics platform.
        </p>

        <h2>Security</h2>      
        <p>The security of your data is important to us, but remember that no method of transmission over the Internet or method of electronic storage is 100% secure.
            While we strive to use commercially acceptable means to protect your data, we cannot guarantee its absolute security.</p> 

        <h2>Changes to This Privacy Policy</h2> 
        <p>We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and send notifications through the Dash.</p>
        <p>You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted on this page.</p>
    </main>
</div>

<style>
main {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
}

h1, h2 {
    margin-top: 20px;
}

h1 {
    font-size: 24px;
    font-weight: bold;
}

h2 {
    font-size: 18px;
    font-weight: bold;
}

h3 {
    font-size: 14px;
    font-weight: bold;
    margin-top: 20px;
}

ul {
    margin-bottom: 20px;
}
</style>
