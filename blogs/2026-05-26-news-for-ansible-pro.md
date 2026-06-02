---
title: News for Ansible Pro
url: https://plugins.jetbrains.com/plugin/31743-ansible-pro
date: '2026-05-26'
author: ''
feed_url: https://plugins.jetbrains.com/rss
---
<h3>2.0.0</h3>
        <ul>
            <li>Major update focused on execution and automation workflows in the IDE.</li>
            <li>Vault flow hardening: transparent decrypted editing in memory with reliable
            re-encrypt on save/close, optional vault-id support, and safer background
            processing outside EDT.</li>
            <li>Playbook execution overhaul: run line marker on playbooks, selectable run
            presets (dry-run, syntax check, tags, start-at-task, inventory), and a
            dedicated <code>ansible-playbook</code> run configuration.</li>
            <li>AAP/AWX integration: connection settings and test, job template listing,
            launch from IDE, and stdout retrieval after completion.</li>
            <li>Inventory and refactoring upgrades: inventory graph action, role-aware
            tag/task pickers, project-relative inventory labels, and vars rename
            propagation across shared vars/inventory usage.</li>
            <li>Tooling and UX updates: Molecule test action, improved action grouping, and
            chooser migration from deprecated APIs.</li>
        </ul>
        <h3>1.0.0</h3>
        <ul>
            <li>First public release after an extended internal hardening cycle.</li>
            <li>Scope-aware activation (only inside Ansible projects, never in Helm /
            Kubernetes / GitHub Actions / Docker Compose).</li>
            <li>Native LSP integration via Red Hat's
            <code>@ansible/ansible-language-server</code>.</li>
            <li>Inventory layer: navigation between inventory keys and
            <code>group_vars</code> / <code>host_vars</code>, back-navigation banner,
            completion of group and host names in playbook <code>hosts:</code>.</li>
            <li>Ansible Vault operations available in the paid tier.</li>
            <li>Settings page with dependency status, in-IDE installer and auto-start of
            the LSP once the binary appears on <code>PATH</code>.</li>
        </ul>
