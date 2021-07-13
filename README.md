# provectories
Redirect `provectories.jku-vds-lab.at` to `provectories.caleydoapp.org`

## Steps

1. Create this repository, the index.html will redirect visitors
2. Enable github pages, this hosts the index.html at:
3. In order to use the subdomain provectories.jku-vds-lab.at instead, create the subdomain in AWS Route 53  
  In AWS, create a CNAME record `provectories.jku-vds-lab.at` with value `jku-vds-lab.github.io` (not repo name, see https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site#configuring-a-subdomain)
4. Set `provectories.jku-vds-lab.at` as custom domain in the repo settings
