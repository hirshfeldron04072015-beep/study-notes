<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport"
      content="width=device-width, initial-scale=1.0,
               maximum-scale=1.0, user-scalable=no">

<title>StudyNotes</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

:root {
    --bg: #101010;
    --panel: #111111;
    --panel-2: #1c1c1c;
    --panel-3: #202020;
    --border: #292929;
    --border-light: #353535;
    --text: #f3f3f3;
    --muted: #858585;
    --muted-2: #5d5d5d;
    --white: #f5f5f5;
}

html,
body {
    width: 100%;
    height: 100%;
    overflow: hidden;
    background: var(--bg);
    color: var(--text);
    font-family:
        -apple-system,
        BlinkMacSystemFont,
        "SF Pro Display",
        "SF Pro Text",
        Inter,
        Helvetica,
        Arial,
        sans-serif;
}

button,
input,
textarea {
    font: inherit;
}

button {
    border: 0;
    background: none;
    color: inherit;
}

button,
.note-item,
.folder-item {
    -webkit-tap-highlight-color: transparent;
}

/* =========================
   APP
========================= */

.app {
    width: 100%;
    height: 100%;
    display: flex;
    background: var(--bg);
}

/* =========================
   SIDEBAR
========================= */

.sidebar {
    width: 488px;
    min-width: 488px;
    height: 100%;
    border-right: 1px solid var(--border);
    background: #111111;
    display: flex;
    flex-direction: column;
    transition:
        width .38s cubic-bezier(.2,.8,.2,1),
        min-width .38s cubic-bezier(.2,.8,.2,1),
        opacity .25s ease;
    overflow: hidden;
    z-index: 10;
}

.sidebar.collapsed {
    width: 0;
    min-width: 0;
    border-right: 0;
    opacity: 0;
}

/* sidebar header */

.sidebar-header {
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 32px;
    flex-shrink: 0;
}

.logo {
    display: flex;
    align-items: center;
    gap: 15px;
}

.logo-mark {
    width: 34px;
    height: 34px;
    border: 2px solid #d7d7d7;
    border-radius: 50%;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
}

.logo-mark::before {
    content: "";
    width: 14px;
    height: 14px;
    background: #d7d7d7;
    border-radius: 50%;
}

.logo-mark::after {
    content: "";
    position: absolute;
    width: 20px;
    height: 20px;
    border: 1px solid #4d4d4d;
    border-radius: 50%;
}

.logo-text {
    font-size: 24px;
    font-weight: 600;
    letter-spacing: -0.7px;
}

.collapse-btn {
    width: 56px;
    height: 56px;
    border-radius: 13px;
    background: #292929;
    border: 1px solid #303030;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    transition: background .2s ease, transform .2s ease;
}

.collapse-btn:hover {
    background: #333;
}

.collapse-btn:active {
    transform: scale(.94);
}

.collapse-icon {
    width: 21px;
    height: 21px;
    border: 2px solid #999;
    border-radius: 2px;
    position: relative;
}

.collapse-icon::after {
    content: "";
    position: absolute;
    top: 3px;
    left: 5px;
    width: 2px;
    height: 11px;
    background: #999;
}

/* space */

.space-section {
    padding: 25px 32px 0;
}

.space-title-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 25px;
}

.space-title {
    font-size: 13px;
    color: #7b7b7b;
    letter-spacing: 1.6px;
    font-weight: 600;
}

.add-folder {
    width: 25px;
    height: 25px;
    border: 2px solid #cfcfcf;
    border-radius: 50%;
    font-size: 18px;
    line-height: 18px;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}

.add-folder:hover {
    background: #292929;
}

/* folders */

.folder-list {
    display: flex;
    flex-direction: column;
    gap: 4px;
}

.folder-item {
    min-height: 58px;
    border-radius: 10px;
    padding: 0 16px;
    display: flex;
    align-items: center;
    gap: 14px;
    cursor: pointer;
    color: #969696;
    transition:
        background .2s ease,
        color .2s ease,
        transform .15s ease;
}

.folder-item:hover {
    background: #181818;
    color: #ddd;
}

.folder-item.active {
    background: #202020;
    color: #e6e6e6;
}

.folder-icon {
    width: 22px;
    height: 18px;
    border: 2px solid currentColor;
    border-radius: 3px;
    position: relative;
    flex-shrink: 0;
}

.folder-icon::before {
    content: "";
    position: absolute;
    width: 8px;
    height: 4px;
    left: -2px;
    top: -6px;
    border: 2px solid currentColor;
    border-bottom: 0;
    border-radius: 3px 3px 0 0;
}

.folder-name {
    flex: 1;
    font-size: 17px;
}

.folder-count {
    color: #777;
    font-size: 14px;
}

.folder-edit {
    opacity: 0;
    cursor: pointer;
    color: #999;
    transition: opacity .2s ease;
}

.folder-item:hover .folder-edit {
    opacity: 1;
}

/* notes section */

.notes-section {
    margin: 20px 20px 0;
    border-top: 1px solid #2b2b2b;
    padding: 28px 16px 0;
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
}

.notes-title-row {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 12px;
}

.notes-title {
    font-size: 37px;
    letter-spacing: -1.5px;
    font-weight: 500;
}

.notes-count {
    color: #777;
    font-size: 15px;
    margin-bottom: 30px;
}

.new-note-btn {
    width: 60px;
    height: 60px;
    border-radius: 14px;
    background: #f2f2f2;
    color: #171717;
    font-size: 30px;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    box-shadow: 0 8px 30px rgba(255,255,255,.08);
    transition:
        transform .2s ease,
        background .2s ease;
}

.new-note-btn:hover {
    background: white;
    transform: translateY(-2px);
}

.new-note-btn:active {
    transform: scale(.94);
}

/* search */

.search-box {
    height: 57px;
    border: 1px solid #3a3a3a;
    border-radius: 12px;
    display: flex;
    align-items: center;
    padding: 0 15px;
    margin-bottom: 20px;
    background: #151515;
    transition: border .2s ease;
}

.search-box:focus-within {
    border-color: #656565;
}

.search-icon {
    color: #8b8b8b;
    font-size: 25px;
    margin-right: 13px;
}

.search-box input {
    background: transparent;
    border: 0;
    outline: 0;
    color: white;
    width: 100%;
    font-size: 16px;
}

.search-box input::placeholder {
    color: #777;
}

/* note list */

.note-list {
    overflow-y: auto;
    flex: 1;
    padding-right: 4px;
}

.note-list::-webkit-scrollbar {
    width: 5px;
}

.note-list::-webkit-scrollbar-thumb {
    background: #333;
    border-radius: 5px;
}

.note-item {
    padding: 17px 14px;
    border-radius: 10px;
    margin-bottom: 5px;
    cursor: pointer;
    transition: background .2s ease;
}

.note-item:hover {
    background: #1b1b1b;
}

.note-item.active {
    background: #232323;
}

.note-item-title {
    font-size: 17px;
    margin-bottom: 7px;
}

.note-item-preview {
    color: #777;
    font-size: 14px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

.note-item-time {
    margin-top: 8px;
    color: #555;
    font-size: 12px;
}

/* empty notes */

.empty-notes {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    color: #ddd;
    padding-bottom: 70px;
}

.empty-icon {
    width: 55px;
    height: 55px;
    border: 1px dashed #454545;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
    color: #aaa;
}

.empty-title {
    font-size: 19px;
    margin-bottom: 13px;
}

.empty-subtitle {
    color: #777;
    font-size: 14px;
    margin-bottom: 28px;
}

.write-link {
    color: #ddd;
    font-size: 16px;
    cursor: pointer;
}

/* =========================
   MAIN
========================= */

.main {
    flex: 1;
    min-width: 0;
    height: 100%;
    position: relative;
    background: #111111;
}

/* reopen button */

.reopen-btn {
    position: absolute;
    left: 35px;
    top: 32px;
    width: 56px;
    height: 56px;
    background: #292929;
    border: 1px solid #303030;
    border-radius: 13px;
    color: #999;
    display: none;
    align-items: center;
    justify-content: center;
    cursor: pointer;
    z-index: 5;
}

.sidebar.collapsed ~ .main .reopen-btn {
    display: flex;
}

/* empty main */

.empty-main {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    transition: opacity .3s ease;
}

.orbit {
    width: 180px;
    height: 180px;
    position: relative;
    margin-bottom: 22px;
}

.orbit-ring {
    position: absolute;
    width: 175px;
    height: 82px;
    border: 1px solid #555;
    border-radius: 50%;
    left: 2px;
    top: 47px;
    transform: rotate(58deg);
}

.orbit-ring.two {
    transform: rotate(-45deg);
}

.orbit-dot {
    position: absolute;
    width: 27px;
    height: 27px;
    border-radius: 50%;
    background: #f0f0f0;
    left: 76px;
    top: 77px;
    box-shadow:
        0 0 0 13px rgba(255,255,255,.06),
        0 0 0 1px #292929;
}

.empty-main h1 {
    font-size: 28px;
    font-weight: 500;
    letter-spacing: -.7px;
    margin-bottom: 18px;
}

.empty-main p {
    color: #777;
    font-size: 16px;
    margin-bottom: 30px;
}

.main-new-note {
    background: #242424;
    border: 1px solid #303030;
    padding: 15px 27px;
    border-radius: 12px;
    font-size: 17px;
    cursor: pointer;
    transition: background .2s ease, transform .2s ease;
}

.main-new-note:hover {
    background: #2c2c2c;
}

.main-new-note:active {
    transform: scale(.96);
}

/* =========================
   EDITOR
========================= */

.editor {
    width: 100%;
    height: 100%;
    display: none;
    flex-direction: column;
    animation: editorIn .3s ease;
}

@keyframes editorIn {
    from {
        opacity: 0;
        transform: translateY(7px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.editor-header {
    height: 90px;
    padding: 0 38px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-bottom: 1px solid #242424;
}

.editor-title {
    background: transparent;
    border: 0;
    outline: 0;
    color: #f5f5f5;
    font-size: 26px;
    font-weight: 500;
    width: 70%;
}

.editor-actions {
    display: flex;
    gap: 8px;
}

.icon-btn {
    width: 42px;
    height: 42px;
    border-radius: 9px;
    color: #888;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
}

.icon-btn:hover {
    background: #222;
    color: #eee;
}

.icon-btn.active {
    color: white;
    background: #282828;
}

.toolbar {
    min-height: 55px;
    border-bottom: 1px solid #242424;
    display: flex;
    align-items: center;
    gap: 5px;
    padding: 0 38px;
    overflow-x: auto;
}

.toolbar button {
    min-width: 38px;
    height: 36px;
    padding: 0 9px;
    border-radius: 7px;
    color: #999;
    cursor: pointer;
}

.toolbar button:hover {
    background: #242424;
    color: white;
}

.toolbar-divider {
    width: 1px;
    height: 23px;
    background: #303030;
    margin: 0 7px;
}

.editor-body {
    flex: 1;
    overflow: hidden;
    display: flex;
    justify-content: center;
}

.editor-content {
    width: min(900px, 90%);
    height: 100%;
    padding: 45px 0 120px;
    overflow-y: auto;
}

.editor-textarea {
    width: 100%;
    min-height: 100%;
    resize: none;
    background: transparent;
    border: 0;
    outline: 0;
    color: #e9e9e9;
    font-size: 18px;
    line-height: 1.75;
    font-family:
        -apple-system,
        BlinkMacSystemFont,
        "SF Pro Text",
        Inter,
        sans-serif;
}

.editor-textarea::placeholder {
    color: #555;
}

/* markdown preview */

.preview {
    display: none;
    color: #e9e9e9;
    font-size: 18px;
    line-height: 1.75;
}

.preview h1,
.preview h2,
.preview h3 {
    margin: 28px 0 12px;
    line-height: 1.2;
}

.preview h1 {
    font-size: 34px;
}

.preview h2 {
    font-size: 27px;
}

.preview h3 {
    font-size: 22px;
}

.preview p {
    margin-bottom: 18px;
}

.preview ul,
.preview ol {
    padding-left: 28px;
    margin-bottom: 18px;
}

.preview blockquote {
    border-left: 3px solid #666;
    padding-left: 18px;
    color: #aaa;
    margin: 20px 0;
}

.preview code {
    background: #202020;
    border-radius: 5px;
    padding: 3px 6px;
}

.preview pre {
    background: #191919;
    border: 1px solid #292929;
    border-radius: 10px;
    padding: 18px;
    overflow-x: auto;
    margin: 20px 0;
}

/* status */

.editor-footer {
    position: absolute;
    bottom: 15px;
    left: 0;
    width: 100%;
    display: flex;
    justify-content: center;
    pointer-events: none;
}

.save-status {
    color: #666;
    font-size: 12px;
}

/* =========================
   MODAL
========================= */

.modal-overlay {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,.65);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 100;
    backdrop-filter: blur(8px);
}

.modal {
    width: min(440px, 90%);
    background: #1b1b1b;
    border: 1px solid #303030;
    border-radius: 17px;
    padding: 25px;
    box-shadow: 0 25px 80px rgba(0,0,0,.5);
    animation: modalIn .22s ease;
}

@keyframes modalIn {
    from {
        opacity: 0;
        transform: scale(.95);
    }
    to {
        opacity: 1;
        transform: scale(1);
    }
}

.modal h2 {
    font-size: 22px;
    margin-bottom: 20px;
}

.modal input {
    width: 100%;
    height: 50px;
    background: #111;
    border: 1px solid #353535;
    border-radius: 9px;
    outline: none;
    padding: 0 14px;
    color: white;
}

.modal-buttons {
    display: flex;
    justify-content: flex-end;
    gap: 9px;
    margin-top: 20px;
}

.modal-buttons button {
    padding: 10px 17px;
    border-radius: 8px;
    cursor: pointer;
}

.cancel-btn {
    background: #252525;
}

.confirm-btn {
    background: #eee;
    color: #111;
}

/* =========================
   CONTEXT MENU
========================= */

.context-menu {
    position: fixed;
    display: none;
    width: 180px;
    background: #202020;
    border: 1px solid #333;
    border-radius: 10px;
    padding: 5px;
    z-index: 200;
    box-shadow: 0 15px 40px rgba(0,0,0,.5);
}

.context-menu button {
    width: 100%;
    text-align: left;
    padding: 10px;
    border-radius: 7px;
    cursor: pointer;
    color: #ccc;
}

.context-menu button:hover {
    background: #2d2d2d;
}

/* =========================
   MOBILE / PORTRAIT
========================= */

@media (max-width: 800px) {

    .sidebar {
        width: 100%;
        min-width: 100%;
        position: absolute;
        left: 0;
        top: 0;
    }

    .sidebar.collapsed {
        width: 0;
        min-width: 0;
    }

    .main {
        width: 100%;
    }

    .editor-content {
        width: 90%;
    }

    .editor-header {
        padding: 0 20px;
    }

    .toolbar {
        padding: 0 20px;
    }

    .editor-title {
        font-size: 21px;
    }
}

/* =========================
   REDUCED MOTION
========================= */

@media (prefers-reduced-motion: reduce) {
    *,
    *::before,
    *::after {
        animation-duration: .01ms !important;
        transition-duration: .01ms !important;
    }
}
</style>
</head>

<body>

<div class="app">

    <!-- ================= SIDEBAR ================= -->

    <aside class="sidebar" id="sidebar">

        <div class="sidebar-header">

            <div class="logo">
                <div class="logo-mark"></div>
                <div class="logo-text">studynotes</div>
            </div>

            <button
                class="collapse-btn"
                onclick="toggleSidebar()"
                aria-label="Collapse sidebar">

                <div class="collapse-icon"></div>

            </button>

        </div>


        <div class="space-section">

            <div class="space-title-row">
                <div class="space-title">YOUR SPACE</div>

                <button
                    class="add-folder"
                    onclick="openFolderModal()">
                    +
                </button>
            </div>

            <div class="folder-list" id="folderList"></div>

        </div>


        <div class="notes-section">

            <div class="notes-title-row">

                <div>
                    <div class="notes-title" id="notesTitle">
                        All notes
                    </div>

                    <div class="notes-count" id="notesCount">
                        0 notes
                    </div>
                </div>

                <button
                    class="new-note-btn"
                    onclick="createNote()">
                    +
                </button>

            </div>


            <div class="search-box">

                <div class="search-icon">⌕</div>

                <input
                    id="searchInput"
                    type="search"
                    placeholder="Search your notes"
                    oninput="renderNotes()">

            </div>


            <div
                class="note-list"
                id="noteList">
            </div>

        </div>

    </aside>


    <!-- ================= MAIN ================= -->

    <main class="main">

        <button
            class="reopen-btn"
            onclick="toggleSidebar()"
            aria-label="Open sidebar">

            <div class="collapse-icon"></div>

        </button>


        <!-- EMPTY STATE -->

        <section
            class="empty-main"
            id="emptyMain">

            <div class="orbit">

                <div class="orbit-ring"></div>
                <div class="orbit-ring two"></div>

                <div class="orbit-dot"></div>

            </div>

            <h1>Start writing</h1>

            <p>Begin with a thought.</p>

            <button
                class="main-new-note"
                onclick="createNote()">

                ＋ &nbsp;New note

            </button>

        </section>


        <!-- EDITOR -->

        <section
            class="editor"
            id="editor">

            <header class="editor-header">

                <input
                    id="editorTitle"
                    class="editor-title"
                    placeholder="Untitled"
                    oninput="updateTitle()">

                <div class="editor-actions">

                    <button
                        class="icon-btn"
                        onclick="togglePin()"
                        id="pinButton"
                        title="Pin">
                        ☆
                    </button>

                    <button
                        class="icon-btn"
                        onclick="togglePreview()"
                        id="previewButton"
                        title="Preview">
                        ◉
                    </button>

                    <button
                        class="icon-btn"
                        onclick="deleteCurrentNote()"
                        title="Delete">
                        ♢
                    </button>

                </div>

            </header>


            <div
                class="toolbar"
                id="toolbar">

                <button onclick="format('bold')" title="Bold">
                    <strong>B</strong>
                </button>

                <button onclick="format('italic')" title="Italic">
                    <em>I</em>
                </button>

                <button onclick="format('underline')" title="Underline">
                    <u>U</u>
                </button>

                <button onclick="format('strike')" title="Strikethrough">
                    <s>S</s>
                </button>

                <div class="toolbar-divider"></div>

                <button onclick="insertText('# ')" title="Heading">
                    H
                </button>

                <button onclick="insertText('- ')" title="Bullet list">
                    •
                </button>

                <button onclick="insertText('1. ')" title="Numbered list">
                    1.
                </button>

                <button onclick="insertText('- [ ] ')" title="Checklist">
                    ☑
                </button>

                <button onclick="insertText('> ')" title="Quote">
                    ❯
                </button>

                <button onclick="insertText('`code`')" title="Code">
                    ‹›
                </button>

                <div class="toolbar-divider"></div>

                <button onclick="insertText('[text](https://example.com)')">
                    ↗
                </button>

            </div>


            <div class="editor-body">

                <div class="editor-content">

                    <textarea
                        id="editorTextarea"
                        class="editor-textarea"
                        placeholder="Start writing..."
                        spellcheck="true"
                        oninput="updateContent()">
                    </textarea>

                    <div
                        id="preview"
                        class="preview">
                    </div>

                </div>

            </div>


            <div class="editor-footer">

                <div
                    class="save-status"
                    id="saveStatus">
                    Saved
                </div>

            </div>

        </section>

    </main>

</div>


<!-- ================= FOLDER MODAL ================= -->

<div
    class="modal-overlay"
    id="folderModal">

    <div class="modal">

        <h2>New folder</h2>

        <input
            id="folderInput"
            placeholder="Folder name"
            onkeydown="if(event.key==='Enter') createFolder()">

        <div class="modal-buttons">

            <button
                class="cancel-btn"
                onclick="closeFolderModal()">
                Cancel
            </button>

            <button
                class="confirm-btn"
                onclick="createFolder()">
                Create
            </button>

        </div>

    </div>

</div>


<script>

/* =====================================================
   DATA
===================================================== */

const STORAGE_KEY = "studynotes-data-v1";

let data = loadData();

let currentNoteId = null;

let currentFolderId = "all";

let previewMode = false;


/* =====================================================
   INITIAL DATA
===================================================== */

function defaultData() {

    return {

        folders: [
            {
                id: "uncategorized",
                name: "Unnamed"
            }
        ],

        notes: []

    };

}


/* =====================================================
   STORAGE
===================================================== */

function loadData() {

    try {

        const saved =
            localStorage.getItem(STORAGE_KEY);

        if (saved) {

            return JSON.parse(saved);

        }

    } catch (error) {

        console.error(error);

    }

    return defaultData();

}


function saveData() {

    localStorage.setItem(
        STORAGE_KEY,
        JSON.stringify(data)
    );

    showSaved();

}


function showSaved() {

    const status =
        document.getElementById("saveStatus");

    if (!status) return;

    status.textContent = "Saved";

}


/* =====================================================
   SIDEBAR
===================================================== */

function toggleSidebar() {

    const sidebar =
        document.getElementById("sidebar");

    sidebar.classList.toggle("collapsed");

}


/* =====================================================
   FOLDERS
===================================================== */

function renderFolders() {

    const list =
        document.getElementById("folderList");

    list.innerHTML = "";


    /* ALL NOTES */

    const all =
        document.createElement("div");

    all.className =
        "folder-item " +
        (currentFolderId === "all"
            ? "active"
            : "");

    all.innerHTML = `

        <div class="folder-icon"
             style="border-radius:2px">
        </div>

        <div class="folder-name">
            All notes
        </div>

        <div class="folder-count">
            ${data.notes.length}
        </div>

    `;

    all.onclick = () => {

        currentFolderId = "all";

        currentNoteId = null;

        updateUI();

    };

    list.appendChild(all);


    /* CUSTOM FOLDERS */

    data.folders.forEach(folder => {

        const count =
            data.notes.filter(
                n => n.folderId === folder.id
            ).length;


        const item =
            document.createElement("div");

        item.className =
            "folder-item " +
            (currentFolderId === folder.id
                ? "active"
                : "");


        item.innerHTML = `

            <div class="folder-icon"></div>

            <div class="folder-name">
                ${escapeHTML(folder.name)}
            </div>

            <div class="folder-count">
                ${count}
            </div>

            <div class="folder-edit">
                ⋯
            </div>

        `;


        item.onclick = () => {

            currentFolderId = folder.id;

            currentNoteId = null;

            updateUI();

        };


        list.appendChild(item);

    });

}


function openFolderModal() {

    document.getElementById(
        "folderModal"
    ).style.display = "flex";

    setTimeout(() => {

        document.getElementById(
            "folderInput"
        ).focus();

    }, 100);

}


function closeFolderModal() {

    document.getElementById(
        "folderModal"
    ).style.display = "none";

    document.getElementById(
        "folderInput"
    ).value = "";

}


function createFolder() {

    const input =
        document.getElementById(
            "folderInput"
        );

    const name =
        input.value.trim();

    if (!name) return;


    data.folders.push({

        id:
            "folder-" +
            Date.now(),

        name

    });


    saveData();

    closeFolderModal();

    renderFolders();

}


/* =====================================================
   NOTES
===================================================== */

function createNote() {

    let folderId =
        currentFolderId === "all"
            ? "uncategorized"
            : currentFolderId;


    const note = {

        id:
            "note-" +
            Date.now(),

        title: "Untitled",

        content: "",

        folderId,

        pinned: false,

        createdAt: Date.now(),

        updatedAt: Date.now()

    };


    data.notes.unshift(note);

    currentNoteId = note.id;

    saveData();

    updateUI();

    setTimeout(() => {

        document
            .getElementById("editorTitle")
            .focus();

    }, 100);

}


function getCurrentNote() {

    return data.notes.find(
        n => n.id === currentNoteId
    );

}


function updateTitle() {

    const note =
        getCurrentNote();

    if (!note) return;

    note.title =
        document
            .getElementById("editorTitle")
            .value ||
        "Untitled";

    note.updatedAt =
        Date.now();

    saveData();

    renderNotes();

}


function updateContent() {

    const note =
        getCurrentNote();

    if (!note) return;

    note.content =
        document
            .getElementById("editorTextarea")
            .value;

    note.updatedAt =
        Date.now();

    document
        .getElementById("saveStatus")
        .textContent = "Saving…";

    clearTimeout(window.saveTimer);

    window.saveTimer =
        setTimeout(() => {

            saveData();

        }, 500);

}


function selectNote(id) {

    currentNoteId = id;

    openEditor();

    renderNotes();

}


function deleteCurrentNote() {

    if (!currentNoteId) return;

    const note =
        getCurrentNote();

    if (!note) return;


    const ok =
        confirm(
            `Delete "${note.title}"?`
        );

    if (!ok) return;


    data.notes =
        data.notes.filter(
            n => n.id !== currentNoteId
        );


    currentNoteId = null;

    saveData();

    updateUI();

}


function togglePin() {

    const note =
        getCurrentNote();

    if (!note) return;

    note.pinned =
        !note.pinned;

    saveData();

    updateEditor();

    renderNotes();

}


/* =====================================================
   NOTE FILTERING
===================================================== */

function getVisibleNotes() {

    const search =
        document
            .getElementById("searchInput")
            .value
            .trim()
            .toLowerCase();


    let notes =
        data.notes.filter(note => {

            const folderMatch =
                currentFolderId === "all" ||
                note.folderId === currentFolderId;

            const searchMatch =
                !search ||
                note.title
                    .toLowerCase()
                    .includes(search) ||
                note.content
                    .toLowerCase()
                    .includes(search);

            return folderMatch &&
                   searchMatch;

        });


    notes.sort((a,b) => {

        if (a.pinned !== b.pinned) {

            return a.pinned ? -1 : 1;

        }

        return b.updatedAt -
               a.updatedAt;

    });


    return notes;

}


/* =====================================================
   RENDER NOTES
===================================================== */

function renderNotes() {

    const list =
        document.getElementById(
            "noteList"
        );

    list.innerHTML = "";


    const notes =
        getVisibleNotes();


    const count =
        document.getElementById(
            "notesCount"
        );


    count.textContent =
        `${notes.length} ${
            notes.length === 1
                ? "note"
                : "notes"
        }`;


    if (notes.length === 0) {

        const empty =
            document.createElement("div");

        empty.className =
            "empty-notes";

        empty.innerHTML = `

            <div class="empty-icon">
                ▤
            </div>

            <div class="empty-title">
                No notes yet
            </div>

            <div class="empty-subtitle">
                Create your first note.
            </div>

            <div
                class="write-link"
                onclick="createNote()">

                Write a note →

            </div>

        `;

        list.appendChild(empty);

        return;

    }


    notes.forEach(note => {

        const item =
            document.createElement("div");

        item.className =
            "note-item " +
            (currentNoteId === note.id
                ? "active"
                : "");


        const preview =
            note.content
                .replace(/\n/g, " ")
                .slice(0, 100);


        item.innerHTML = `

            <div class="note-item-title">

                ${note.pinned ? "☆ " : ""}

                ${escapeHTML(
                    note.title || "Untitled"
                )}

            </div>

            <div class="note-item-preview">

                ${escapeHTML(
                    preview ||
                    "No content"
                )}

            </div>

            <div class="note-item-time">

                ${formatDate(note.updatedAt)}

            </div>

        `;


        item.onclick = () => {

            selectNote(note.id);

        };


        item.oncontextmenu =
            event => {

                event.preventDefault();

                showContextMenu(
                    event,
                    note.id
                );

            };


        list.appendChild(item);

    });

}


/* =====================================================
   EDITOR
===================================================== */

function openEditor() {

    document
        .getElementById("emptyMain")
        .style.display = "none";

    document
        .getElementById("editor")
        .style.display = "flex";

    updateEditor();

}


function updateEditor() {

    const note =
        getCurrentNote();

    if (!note) {

        closeEditor();

        return;

    }


    document
        .getElementById("editorTitle")
        .value =
        note.title || "Untitled";


    document
        .getElementById("editorTextarea")
        .value =
        note.content || "";


    const pin =
        document.getElementById(
            "pinButton"
        );

    pin.textContent =
        note.pinned
            ? "★"
            : "☆";


    if (previewMode) {

        updatePreview();

    }

}


function closeEditor() {

    document
        .getElementById("editor")
        .style.display = "none";

    document
        .getElementById("emptyMain")
        .style.display = "flex";

}


function togglePreview() {

    previewMode =
        !previewMode;


    const textarea =
        document.getElementById(
            "editorTextarea"
        );

    const preview =
        document.getElementById(
            "preview"
        );

    const toolbar =
        document.getElementById(
            "toolbar"
        );


    if (previewMode) {

        textarea.style.display =
            "none";

        toolbar.style.display =
            "none";

        preview.style.display =
            "block";

        updatePreview();

    } else {

        textarea.style.display =
            "block";

        toolbar.style.display =
            "flex";

        preview.style.display =
            "none";

    }


    document
        .getElementById(
            "previewButton"
        )
        .classList.toggle(
            "active",
            previewMode
        );

}


function updatePreview() {

    const content =
        document
            .getElementById(
                "editorTextarea"
            )
            .value;

    document
        .getElementById("preview")
        .innerHTML =
        markdownToHTML(content);

}


/* =====================================================
   MARKDOWN
===================================================== */

function markdownToHTML(text) {

    let html =
        escapeHTML(text);


    /* code blocks */

    html =
        html.replace(
            /```([\s\S]*?)```/g,
            "<pre>$1</pre>"
        );


    /* headings */

    html =
        html.replace(
            /^### (.*)$/gm,
            "<h3>$1</h3>"
        );

    html =
        html.replace(
            /^## (.*)$/gm,
            "<h2>$1</h2>"
        );

    html =
        html.replace(
            /^# (.*)$/gm,
            "<h1>$1</h1>"
        );


    /* bold */

    html =
        html.replace(
            /\*\*(.*?)\*\*/g,
            "<strong>$1</strong>"
        );


    /* italic */

    html =
        html.replace(
            /\*(.*?)\*/g,
            "<em>$1</em>"
        );


    /* strikethrough */

    html =
        html.replace(
            /~~(.*?)~~/g,
            "<s>$1</s>"
        );


    /* inline code */

    html =
        html.replace(
            /`([^`]+)`/g,
            "<code>$1</code>"
        );


    /* links */

    html =
        html.replace(
            /$begin:math:display$\(\[\^$end:math:display$]+)\]$begin:math:text$\(\[\^\)\]\+\)$end:math:text$/g,
            '<a href="$2" target="_blank">$1</a>'
        );


    /* line processing */

    const lines =
        html.split("\n");

    let output = "";

    let inList = false;


    lines.forEach(line => {

        if (/^- /.test(line)) {

            if (!inList) {

                output += "<ul>";

                inList = true;

            }

            output +=
                "<li>" +
                line.slice(2) +
                "</li>";

            return;

        }


        if (inList) {

            output += "</ul>";

            inList = false;

        }


        if (
            line.trim() === ""
        ) {

            output += "<br>";

        } else if (
            !line.startsWith("<h") &&
            !line.startsWith("<pre")
        ) {

            output +=
                "<p>" +
                line +
                "</p>";

        } else {

            output += line;

        }

    });


    if (inList) {

        output += "</ul>";

    }


    return output;

}


/* =====================================================
   FORMATTING
===================================================== */

function insertText(text) {

    const textarea =
        document.getElementById(
            "editorTextarea"
        );

    const start =
        textarea.selectionStart;

    const end =
        textarea.selectionEnd;

    const before =
        textarea.value.slice(
            0,
            start
        );

    const selected =
        textarea.value.slice(
            start,
            end
        );

    const after =
        textarea.value.slice(
            end
        );


    textarea.value =
        before +
        text.replace(
            "text",
            selected || "text"
        ) +
        after;


    textarea.focus();


    const position =
        start +
        text.length;


    textarea.selectionStart =
        position;

    textarea.selectionEnd =
        position;


    updateContent();

}


function format(type) {

    const textarea =
        document.getElementById(
            "editorTextarea"
        );


    const start =
        textarea.selectionStart;

    const end =
        textarea.selectionEnd;


    const selected =
        textarea.value.slice(
            start,
            end
        );


    if (!selected) return;


    let wrapper = "";


    if (type === "bold")
        wrapper = "**";

    if (type === "italic")
        wrapper = "*";

    if (type === "underline")
        wrapper = "<u>";

    if (type === "strike")
        wrapper = "~~";


    let result;


    if (type === "underline") {

        result =
            "<u>" +
            selected +
            "</u>";

    } else {

        result =
            wrapper +
            selected +
            wrapper;

    }


    textarea.value =
        textarea.value.slice(
            0,
            start
        ) +
        result +
        textarea.value.slice(
            end
        );


    textarea.focus();

    updateContent();

}


/* =====================================================
   KEYBOARD SHORTCUTS
===================================================== */

document.addEventListener(
    "keydown",
    event => {

        if (
            (event.metaKey ||
             event.ctrlKey) &&
            event.key.toLowerCase() === "n"
        ) {

            event.preventDefault();

            createNote();

        }


        if (
            (event.metaKey ||
             event.ctrlKey) &&
            event.key.toLowerCase() === "f"
        ) {

            event.preventDefault();

            document
                .getElementById(
                    "searchInput"
                )
                .focus();

        }


        if (
            event.key === "Escape"
        ) {

            document
                .getElementById(
                    "folderModal"
                )
                .style.display =
                "none";

            hideContextMenu();

        }

    }
);


/* =====================================================
   CONTEXT MENU
===================================================== */

let contextNoteId = null;


function showContextMenu(
    event,
    noteId
) {

    contextNoteId = noteId;


    let menu =
        document.getElementById(
            "contextMenu"
        );


    if (!menu) {

        menu =
            document.createElement(
                "div"
            );

        menu.id =
            "contextMenu";

        menu.className =
            "context-menu";

        menu.innerHTML = `

            <button onclick="duplicateNote()">
                Duplicate
            </button>

            <button onclick="toggleContextPin()">
                Pin / unpin
            </button>

            <button onclick="deleteContextNote()">
                Delete
            </button>

        `;

        document.body.appendChild(menu);

    }


    menu.style.display =
        "block";

    menu.style.left =
        event.clientX + "px";

    menu.style.top =
        event.clientY + "px";

}


function hideContextMenu() {

    const menu =
        document.getElementById(
            "contextMenu"
        );

    if (menu)
        menu.style.display =
            "none";

}


document.addEventListener(
    "click",
    hideContextMenu
);


function duplicateNote() {

    const original =
        data.notes.find(
            n => n.id === contextNoteId
        );

    if (!original) return;


    const copy = {

        ...original,

        id:
            "note-" +
            Date.now(),

        title:
            original.title +
            " copy",

        createdAt:
            Date.now(),

        updatedAt:
            Date.now()

    };


    data.notes.unshift(copy);

    saveData();

    renderNotes();

}


function toggleContextPin() {

    const note =
        data.notes.find(
            n => n.id === contextNoteId
        );

    if (!note) return;


    note.pinned =
        !note.pinned;


    saveData();

    renderNotes();

}


function deleteContextNote() {

    data.notes =
        data.notes.filter(
            n => n.id !== contextNoteId
        );


    if (
        currentNoteId ===
        contextNoteId
    ) {

        currentNoteId = null;

    }


    saveData();

    updateUI();

}


/* =====================================================
   UI
===================================================== */

function updateUI() {

    renderFolders();

    renderNotes();


    if (currentNoteId) {

        openEditor();

    } else {

        closeEditor();

    }


    updateNotesTitle();

}


function updateNotesTitle() {

    const title =
        document.getElementById(
            "notesTitle"
        );


    if (
        currentFolderId === "all"
    ) {

        title.textContent =
            "All notes";

        return;

    }


    const folder =
        data.folders.find(
            f =>
                f.id ===
                currentFolderId
        );


    title.textContent =
        folder
            ? folder.name
            : "All notes";

}


/* =====================================================
   UTILITIES
===================================================== */

function formatDate(timestamp) {

    const date =
        new Date(timestamp);


    const now =
        new Date();


    const diff =
        now - date;


    const minutes =
        Math.floor(
            diff / 60000
        );


    if (minutes < 1)
        return "just now";

    if (minutes < 60)
        return `${minutes}m ago`;


    const hours =
        Math.floor(
            minutes / 60
        );


    if (hours < 24)
        return `${hours}h ago`;


    const days =
        Math.floor(
            hours / 24
        );


    if (days < 7)
        return `${days}d ago`;


    return date.toLocaleDateString();

}


function escapeHTML(value) {

    return String(value)
        .replace(
            /&/g,
            "&amp;"
        )
        .replace(
            /</g,
            "&lt;"
        )
        .replace(
            />/g,
            "&gt;"
        )
        .replace(
            /"/g,
            "&quot;"
        )
        .replace(
            /'/g,
            "&#039;"
        );

}


/* =====================================================
   START
===================================================== */

updateUI();

</script>

</body>
</html>