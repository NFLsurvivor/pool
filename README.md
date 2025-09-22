import React from "react";

// This file is the React code for your Survivor app. To publish on GitHub Pages with a custom domain,
// you just need to add a simple `CNAME` file in your repository root with your domain name inside.

// Example: if you want your site on survivor.366days.ca
// Create a file called `CNAME` (no extension) in the root of the repo with this content:
// survivor.366days.ca

// GitHub Pages will automatically configure it for you once DNS is set up.

// The rest of your React app remains unchanged.

export default function App() {
  return (
    <div className="p-6">
      <h1 className="text-2xl font-bold">NFL Survivor App</h1>
      <p className="mt-2 text-slate-600">
        Your pool app is ready. To finish publishing with your custom domain,
        be sure to add a <code>CNAME</code> file in your GitHub Pages repo root with
        your domain name.
      </p>
    </div>
  );
}
