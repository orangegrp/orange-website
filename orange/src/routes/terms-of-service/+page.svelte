<!-- src/routes/terms-of-service.svelte -->

<script>
    export let lastUpdated = "28/12/2023";
</script>

<div>
    <main>
        <h1>Terms of Service</h1>
        <p>Last updated: {lastUpdated}</p> 
        <p>orange🟠 by 332 ("us", "we", or "our") operates Internet services (the "Services") as follows:</p>
        <ul class="list-disc ml-8">
            <li>orange🟠 "Discord" Bot (the "Bot")</li>
            <li>orange🟠 Code Runner Server (the "CRS", "orange🟠 CRS")</li>
            <li>orange🟠 Dash (the "Dash", "dashboard", "control panel", "admin panel")</li>
        </ul>

        <p>
            By using the Services, you agree to comply
            with and be bound by the following terms and conditions. If you do
            not agree to these terms, please do not use the Services.
        </p>

        <h2>1. Use of the Services</h2>
        <p>
            You must only use the Services in accordance with applicable laws and
            regulations and must not engage in any activity that may disrupt,
            damage, or interfere with the functionality of the Services.
        </p>

        <h2>2. User Conduct</h2>
        <p>When using the Services, you agree not to:</p>
        <ul class="list-disc ml-8">
            <li>Violate any applicable laws or regulations.</li>
            <li>Harass, threaten, or harm other users.</li>
            <li>
                Attempt to gain unauthorised access to the Services or its
                related systems.
            </li>
            <li>Use the Services for any illegal or unauthorised purpose.</li>
            <li>
                Engage in any activity that could compromise the security of the
                Services.
            </li>
        </ul>
        <p>
            In addition to our own policies, users of our service must abide by the terms set out by our upstream providers (where applicable).
            The upstream providers are:
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
            <li>Vercel Inc.</li>      
        </ul>

        <h2>3. Intellectual Property</h2>
        <p>
            The Services and its original content, features, and functionality
            are owned by us and are protected by international
            copyright, trademark, patent, trade secret, and other intellectual
            property or proprietary rights laws.
        </p>

        <h2>4. Limitation of Liability</h2>
        <p>
            We shall not be liable for any indirect, incidental,
            special, consequential, or punitive damages, or any loss of profits
            or revenues, whether incurred directly or indirectly, or any loss of
            data, use, goodwill, or other intangible losses resulting from your
            use of the Services.
        </p>

        <h2>5. Termination</h2>
        <p>
            We reserve the right to terminate or suspend your access
            to the Services at any time, without notice, for any reason,
            including without limitation, a breach of these Terms.
        </p>

        <h2>6. Changes to Terms</h2>
        <p>
            We may revise these terms at any time without notice. By
            using the Services, you agree to be bound by the current version of
            these terms.
        </p>
    </main>
</div>

<style>
    main {
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
    }

    h1,
    h2 {
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
