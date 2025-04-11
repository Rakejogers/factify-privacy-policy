# Privacy Policy for Factify Chrome Extension

**Last Updated:** 4/11/2025

Thank you for using Factify! This Privacy Policy explains how we handle information when you use our Chrome extension. Our goal is to be transparent about the data involved in providing our fact-checking service while respecting your privacy.

## 1. Information We Collect

Factify is designed to minimize data collection. Here's what information is involved:

*   **User-Provided Information:**
    *   **Perplexity API Key:** To use the core fact-checking feature, you need to provide your own API key from Perplexity AI. This key is stored **only locally** on your computer using Chrome's secure storage (`chrome.storage.local`) and is **never transmitted to us**. It is sent directly from your browser to Perplexity AI when you request a fact-check.
*   **Information Processed During Use:**
    *   **Selected Text or Page Content:** When you select text and request a fact-check, or use the "Scan Webpage" feature, that text content is sent directly to the Perplexity AI API for analysis. For page scans, the text content of the page (`document.body.innerText`) is processed.
    *   **Active Tab Hostname:** When using "Scan Webpage", the hostname (e.g., `example.com`) of the current webpage may be used as a temporary label for the analysis results stored locally.
*   **Information for Community Features (Optional):**
    *   **Fact-Check Data:** If you choose to "Post to Community Hall", the text you had analyzed (or the placeholder hostname for full-page scans), the resulting truthfulness score, bias score, reasoning, and any citations provided by the API are saved to our public database.
    *   **Anonymous User ID:** A unique, randomly generated ID is created and stored locally (`chrome.storage.local`). This ID is used solely to associate your votes (likes/dislikes) with your browser instance within the Community Hall feature, preventing duplicate votes. It is not linked to any personal information.
    *   **Votes:** When you vote (like/dislike) on a fact-check in the Community Hall, your vote and your anonymous User ID are recorded in our database.
*   **Locally Stored Data:**
    *   Your Perplexity API Key.
    *   Cached analysis results (including text, scores, reasoning, citations) to improve performance and avoid repeat API calls.
    *   Your anonymous User ID.
    *   Flags indicating analysis status (e.g., `shouldAnalyze`).

## 2. How We Use Information

*   **To Provide Core Functionality:** Your API key and the selected/page text are used to communicate with the Perplexity AI API to perform fact-checking analysis.
*   **To Display Results:** Analysis results (scores, reasoning, citations) are displayed to you within the extension's side panel.
*   **To Cache Results:** Analysis results are stored locally to avoid unnecessary API calls for previously checked text.
*   **To Enable Community Features:** If you post to the Community Hall, the fact-check data is stored publicly. Your anonymous User ID and votes are used to manage the community voting system.
*   **To Improve User Experience:** Caching and local storage help the extension operate efficiently.

## 3. Information Sharing and Disclosure

We are committed to not selling your personal information. Sharing is limited to the following:

*   **Perplexity AI:** The text you want to fact-check and your Perplexity API key are sent directly to Perplexity AI's API (`https://api.perplexity.ai`) to perform the analysis. We recommend reviewing [Perplexity AI's Privacy Policy](https://www.perplexity.ai/privacy) for how they handle data.
*   **Supabase (Community Hall):**
    *   Fact-checks you *explicitly choose* to post (text/placeholder, scores, reasoning, citations) are stored in our public database hosted by Supabase and are accessible to other users via the Community Hall feature.
    *   Your votes and the associated anonymous User ID are stored in the Supabase database to manage the voting system.
*   **No Other Sharing:** We do not share your API key, browsing history, cached results (unless posted by you), or anonymous User ID with any other third parties.

## 4. Data Storage and Security

*   **Local Storage:** Your API key, cached results, and anonymous User ID are stored locally on your device using `chrome.storage.local`. This data remains on your computer unless you clear your browser's storage for the extension.
*   **Transmission Security:** Communication with the Perplexity AI API and our Supabase database uses HTTPS encryption.
*   **Community Data:** Data posted to the Community Hall is stored securely within our Supabase project instance.

## 5. User Choices and Control

*   **API Key:** You can choose whether or not to provide a Perplexity API key. The core fact-checking feature requires it. You can remove or update the key at any time via the extension's interface.
*   **Fact-Checking:** You control when to initiate a fact-check by selecting text or clicking the "Scan Webpage" button.
*   **Community Posting:** Posting fact-checks to the Community Hall is optional and requires explicit action ("Post to Community Hall" button).
*   **Clearing Data:** You can clear all locally stored data (API key, cache, User ID) by removing the extension or by clearing the extension's storage through your browser's settings.

## 6. Children's Privacy

Factify is not intended for use by children under the age of 13. We do not knowingly collect any personal information from children under 13.

## 7. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any significant changes by updating the "Last Updated" date at the top of this policy. We encourage you to review this policy periodically.

## 8. Contact Us

If you have any questions about this Privacy Policy, please contact us at [my email](jarog2005@gmail.com).
