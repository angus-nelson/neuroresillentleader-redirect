# Neuro Resilient Leader Redirect

This project redirects all traffic from neuroresillentleader.com to angusnelson.com, preserving the path and query parameters.

## How it works

The `index.html` file contains a simple JavaScript redirect that:
1. Captures the current path, search parameters, and hash
2. 2. Redirects to angusnelson.com with all parameters preserved
   3. 3. If someone visits `neuroresillentleader.com/next`, they are redirected to `angusnelson.com/next`
     
      4. This is deployed on Netlify with the custom domain `neuroresillentleader.com`.
