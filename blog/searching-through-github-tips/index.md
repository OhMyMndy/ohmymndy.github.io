<!--
.. title: Searching through GitHub tips
.. slug: searching-through-github-tips
.. date: 2025-02-17 12:19:19 UTC+01:00
.. tags:
.. category:
.. link:
.. description:
.. type: text
-->

Quick GitHub and Sourcegraph search tip!

As an open-source enthusiast, I hate reinventing the wheel. When I want to run something in my Homelab, I try to find similar configurations to base mine on.

Today I wanted to run Minio, mainly because I want to use it as an S3 compatible backend for Terraform state files.

But, how do I set this up with Docker Compose?

Looking for Docker Compose files with "minio" in the content or filename can be done on GitHub with the search query:
`path:/docker-compose\.ya?ml/ minio`

On Sourcegraph, the same thing can be done with:
`context:global path:docker-compose.ya?ml minio`

![Search for Docker Compose files with "minio" in the title or content on GitHub](/images/github-search.png)
![Search for Docker Compose files with "minio" in the title or content on Sourcegraph](/images/sourcegraph-search.png)
