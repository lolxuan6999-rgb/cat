Here is a complete summary of everything we accomplished and finalized for Track 2: Mobile Data Performance Test Log in your Neighbourhood Cat Journal project:

1. Hardware & Network Adjustments

• Device & Network Reality: Because you tested on an Apple iPhone 11 Pro Max, which lacks a 5G modem, we updated the network environment benchmark from 5G to 4G LTE Cellular Data (3 Bars).
• Why It Still Passes: 4G LTE represents realistic everyday resident hardware, and Padlet's free tier easily supports uploads up to 20 MB.

2. Payload Volume Solution

• Overcoming Small Image Sizes: Your existing photos were under 1 MB (122 KB – 194 KB), which only tested server connection delay rather than actual cellular bandwidth.
• The Fix: You recorded a short 6.1 MB video on your iPhone, which comfortably fits the 5 MB – 10 MB heavy media footprint needed to stress-test sustained mobile upload speeds.

3. Upload Speed & Verification Method

• Simple Capture Without a Mac: Instead of complex browser developer tools or desktop terminals, you used your iPhone's Screen Recording + Stopwatch alongside the native iOS Photos Info Card to verify the exact file size and timing.
• Final Result: Your 6.1 MB video uploaded in 7.98 seconds (~6.12 Mbps sustained throughput), passing well under your 12-second user abandonment threshold.

4. UI & Scroll Stability Adjustment

• Modal Behavior Clarified: During the upload, Padlet locks background scrolling inside a full-screen mobile post editor while showing a live progress bar (Uploading...).
• Accurate Test Execution: You verified UI responsiveness during the upload and confirmed smooth, stutter-free scrolling on the main board immediately after tapping Submit.

5. Final Deliverable Ready for GitHub

• All of these real-world adjustments, metrics, and collapsible <details> screenshot placeholders have been merged into a clean, copy-pasteable GitHub-flavored Markdown log with an official PASSED verdict.
