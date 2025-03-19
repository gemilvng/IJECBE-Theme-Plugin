# Folder structure
```
.
├── common
│   ├── formErrors.tpl
│   └── frontend
│       └── footer.tpl
├── frontend
│   ├── components
│   │   ├── announcements.tpl
│   │   ├── breadcrumbs_announcement.tpl
│   │   ├── breadcrumbs_article.tpl
│   │   ├── breadcrumbs_catalog.tpl
│   │   ├── breadcrumbs_issue.tpl
│   │   ├── breadcrumbs.tpl
│   │   ├── editLink.tpl
│   │   ├── footer.tpl
│   │   ├── header.tpl
│   │   ├── navigationMenus
│   │   │   └── dashboardMenuItem.tpl
│   │   ├── navigationMenu.tpl
│   │   ├── notification.tpl
│   │   ├── pagination.tpl
│   │   ├── registrationFormContexts.tpl
│   │   ├── registrationForm.tpl
│   │   ├── searchFilter.tpl
│   │   └── searchForm_simple.tpl
│   ├── objects
│   │   ├── announcement_full.tpl
│   │   ├── announcement_summary.tpl
│   │   ├── article_details.tpl
│   │   ├── article_summary.tpl
│   │   ├── galley_link.tpl
│   │   ├── issue_summary.tpl
│   │   └── issue_toc.tpl
│   └── pages
│       ├── about.tpl
│       ├── catalogCategory.tpl
│       ├── editorialTeam.tpl
│       ├── indexJournal.tpl
│       ├── indexSite.tpl
│       ├── issueArchive.tpl
│       ├── issue.tpl
│       ├── navigationMenuItemViewContent.tpl
│       ├── purchaseIndividualSubscription.tpl
│       ├── purchaseInstitutionalSubscription.tpl
│       ├── search.tpl
│       ├── submissions.tpl
│       ├── userLogin.tpl
│       ├── userLostPassword.tpl
│       └── userRegister.tpl
├── plugins
│   └── generic
│       └── citationStyleLanguage
│           └── citationblock.tpl
└── README.md

11 directories, 43 files
```
# Penjelasan
Ada tiga subfolder di bawah folder `bootstrap3/templates/`, yaitu `common/`, `frontend/` dan `plugins/`.
## Folder `common/`
Folder `common/` memiliki dua file:
1. `bootstrap3/templates/common/frontend/footer.tpl`: Di sini `footer.tpl` akan menambahkan logo OJS dan meng-include file `bootstrap3/templates/frontend/components/footer.tpl`.
2. `bootstrap3/templates/common/formErrors.tpl`. Meng-handle error selama user mengakses user interface. Mengecek error dengan `$isError` dan mengambil pesan error generic OJS yang sesuai dengan konteks, via `$error`.