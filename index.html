<!DOCTYPE html>
<html lang="uk" class="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Персональна Вікіпедія</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        wikiblue: {
                            DEFAULT: '#36c',
                            dark: '#6b9eff'
                        },
                        wikired: {
                            DEFAULT: '#ba0000',
                            dark: '#ff6b6b'
                        },
                        wikibg: {
                            light: '#f8f9fa',
                            dark: '#101418'
                        },
                        wikicard: {
                            light: '#ffffff',
                            dark: '#1f2328'
                        },
                        wikiborder: {
                            light: '#a2d9ce',
                            dark: '#3c4043'
                        }
                    }
                }
            }
        }
    </script>
    <!-- Font Awesome icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Linux Libertine style serif for titles and Sans for body -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Linux+Libertine&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
        }
        .wiki-heading {
            font-family: 'Linux Libertine', Georgia, Times, serif;
        }
        
        /* Custom scrollbars */
        ::-webkit-scrollbar {
            width: 8px;
            height: 8px;
        }
        ::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.05);
        }
        ::-webkit-scrollbar-thumb {
            background: rgba(0, 0, 0, 0.2);
            border-radius: 4px;
        }
        .dark ::-webkit-scrollbar-thumb {
            background: rgba(255, 255, 255, 0.2);
        }

        /* Article content formatted styles */
        .article-body h1 {
            font-size: 1.75rem;
            font-weight: normal;
            border-bottom: 1px solid #a2a9b1;
            padding-bottom: 0.25rem;
            margin-top: 1.5rem;
            margin-bottom: 0.75rem;
            font-family: 'Linux Libertine', Georgia, serif;
        }
        .dark .article-body h1 {
            border-bottom-color: #444c56;
        }

        .article-body h2 {
            font-size: 1.4rem;
            font-weight: normal;
            border-bottom: 1px solid #eaecf0;
            padding-bottom: 0.2rem;
            margin-top: 1.25rem;
            margin-bottom: 0.5rem;
            font-family: 'Linux Libertine', Georgia, serif;
        }
        .dark .article-body h2 {
            border-bottom-color: #373e47;
        }

        .article-body h3 {
            font-size: 1.15rem;
            font-weight: bold;
            margin-top: 1rem;
            margin-bottom: 0.5rem;
        }

        .article-body p {
            margin-bottom: 0.85rem;
            line-height: 1.6;
        }

        .article-body ul {
            list-style-type: disc;
            padding-left: 1.5rem;
            margin-bottom: 0.85rem;
        }

        .article-body ol {
            list-style-type: decimal;
            padding-left: 1.5rem;
            margin-bottom: 0.85rem;
        }

        .article-body blockquote {
            border-left: 4px solid #36c;
            padding-left: 1rem;
            margin-left: 0;
            margin-right: 0;
            margin-bottom: 1rem;
            font-style: italic;
            color: #54595d;
        }
        .dark .article-body blockquote {
            border-left-color: #6b9eff;
            color: #adbac7;
        }

        /* Wiki link styles */
        .wiki-link-exist {
            color: #36c;
            text-decoration: none;
        }
        .wiki-link-exist:hover {
            text-decoration: underline;
        }
        .dark .wiki-link-exist {
            color: #6b9eff;
        }

        .wiki-link-missing {
            color: #ba0000;
            text-decoration: none;
        }
        .wiki-link-missing:hover {
            text-decoration: underline;
        }
        .dark .wiki-link-missing {
            color: #ff6b6b;
        }

        /* Image embedding in article */
        .article-img-container {
            border: 1px solid #c8ccd1;
            background-color: #f8f9fa;
            padding: 4px;
            margin: 0.5rem 0 1rem 1rem;
            float: right;
            max-width: 300px;
        }
        .dark .article-img-container {
            border-color: #444c56;
            background-color: #22272e;
        }
    </style>
</head>
<body class="bg-wikibg-light dark:bg-wikibg-dark text-slate-800 dark:text-slate-200 min-h-screen transition-colors duration-200 flex flex-col">

    <!-- Top Header Bar -->
    <header class="bg-white dark:bg-[#1c2128] border-b border-gray-200 dark:border-gray-800 sticky top-0 z-30 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-16 flex items-center justify-between gap-4">
            
            <!-- Left: Toggle Sidebar + Logo -->
            <div class="flex items-center space-x-3">
                <button id="sidebarToggleBtn" class="p-2 rounded-lg text-gray-600 dark:text-gray-300 hover:bg-gray-100 dark:hover:bg-gray-800 focus:outline-none" title="Меню">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>
                <a href="javascript:void(0)" onclick="app.goHome()" class="flex items-center gap-2 group">
                    <div class="w-9 h-9 rounded bg-slate-100 dark:bg-slate-800 flex items-center justify-center border border-gray-300 dark:border-gray-700 shadow-inner group-hover:border-wikiblue">
                        <span class="wiki-heading font-serif text-2xl font-bold text-wikiblue dark:text-wikiblue-dark">W</span>
                    </div>
                    <div class="hidden sm:block">
                        <span class="wiki-heading text-lg font-semibold tracking-wide block leading-none">Вікіпедія</span>
                        <span class="text-[10px] text-gray-500 dark:text-gray-400 uppercase tracking-wider font-medium">Вільна енциклопедія</span>
                    </div>
                </a>
            </div>

            <!-- Center: Search Input -->
            <div class="flex-1 max-w-xl relative">
                <div class="relative">
                    <input type="text" id="searchInput" placeholder="Пошук у Вікіпедії..." 
                           class="w-full bg-gray-100 dark:bg-gray-800 text-gray-800 dark:text-gray-100 rounded-full pl-10 pr-10 py-1.5 text-sm border border-transparent focus:border-wikiblue dark:focus:border-wikiblue-dark focus:bg-white dark:focus:bg-gray-900 focus:outline-none transition-all shadow-inner"
                           onkeyup="app.handleSearchKeyUp(event)"
                           oninput="app.handleSearchInput(this.value)">
                    <div class="absolute inset-y-0 left-0 pl-3.5 flex items-center pointer-events-none text-gray-400">
                        <i class="fa-solid fa-magnifying-glass text-xs"></i>
                    </div>
                    <button id="clearSearchBtn" onclick="app.clearSearch()" class="hidden absolute inset-y-0 right-0 pr-3 flex items-center text-gray-400 hover:text-gray-600 dark:hover:text-gray-200">
                        <i class="fa-solid fa-xmark text-sm"></i>
                    </button>
                </div>

                <!-- Live Search Suggestions Dropdown -->
                <div id="searchResults" class="hidden absolute left-0 right-0 top-full mt-1 bg-white dark:bg-[#22272e] border border-gray-200 dark:border-gray-700 rounded-lg shadow-xl z-50 overflow-hidden max-h-80 overflow-y-auto">
                    <!-- Dynamic Search items inserted here -->
                </div>
            </div>

            <!-- Right: Actions & Theme Toggle -->
            <div class="flex items-center space-x-2 sm:space-x-3">
                <button onclick="app.openNewArticleModal()" class="bg-wikiblue hover:bg-blue-700 text-white text-xs sm:text-sm font-medium px-3 py-1.5 rounded flex items-center gap-1.5 shadow-sm transition-colors">
                    <i class="fa-solid fa-plus text-xs"></i>
                    <span class="hidden sm:inline">Створити</span>
                </button>

                <!-- Dark / Light Theme Toggle -->
                <button id="themeToggleBtn" onclick="app.toggleTheme()" class="p-2 rounded-lg text-gray-600 dark:text-gray-300 hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors" title="Змінити тему">
                    <i class="fa-solid fa-moon text-lg dark:hidden"></i>
                    <i class="fa-solid fa-sun text-lg hidden dark:block text-amber-400"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Main Body Container -->
    <div class="flex-1 max-w-7xl w-full mx-auto px-4 sm:px-6 lg:px-8 flex gap-6 pt-4 pb-12">

        <!-- Left Navigation Sidebar -->
        <aside id="sidebar" class="w-64 flex-shrink-0 hidden md:block transition-all duration-300">
            <div class="sticky top-20 space-y-6">
                
                <!-- Main Links Box -->
                <div class="bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-lg p-3 shadow-sm">
                    <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2 px-2">Навігація</div>
                    <nav class="space-y-1">
                        <a href="javascript:void(0)" onclick="app.goHome()" class="flex items-center gap-2.5 px-2.5 py-1.5 rounded text-sm font-medium hover:bg-gray-100 dark:hover:bg-gray-800 text-gray-700 dark:text-gray-200 transition-colors">
                            <i class="fa-solid fa-house w-4 text-center text-wikiblue"></i>
                            <span>Головна сторінка</span>
                        </a>
                        <a href="javascript:void(0)" onclick="app.showAllArticles()" class="flex items-center gap-2.5 px-2.5 py-1.5 rounded text-sm font-medium hover:bg-gray-100 dark:hover:bg-gray-800 text-gray-700 dark:text-gray-200 transition-colors">
                            <i class="fa-solid fa-list-ul w-4 text-center text-emerald-500"></i>
                            <span>Усі сторінки</span>
                        </a>
                        <a href="javascript:void(0)" onclick="app.openRandomArticle()" class="flex items-center gap-2.5 px-2.5 py-1.5 rounded text-sm font-medium hover:bg-gray-100 dark:hover:bg-gray-800 text-gray-700 dark:text-gray-200 transition-colors">
                            <i class="fa-solid fa-shuffle w-4 text-center text-purple-500"></i>
                            <span>Випадкова стаття</span>
                        </a>
                        <a href="javascript:void(0)" onclick="app.showBackupView()" class="flex items-center gap-2.5 px-2.5 py-1.5 rounded text-sm font-medium hover:bg-gray-100 dark:hover:bg-gray-800 text-gray-700 dark:text-gray-200 transition-colors">
                            <i class="fa-solid fa-database w-4 text-center text-amber-500"></i>
                            <span>Експорт / Імпорт</span>
                        </a>
                    </nav>
                </div>

                <!-- Recent Articles Box -->
                <div class="bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-lg p-3 shadow-sm">
                    <div class="text-xs font-bold text-gray-400 uppercase tracking-wider mb-2 px-2">Останні статті</div>
                    <ul id="recentArticlesList" class="space-y-1 text-xs">
                        <!-- Dynamically populated -->
                    </ul>
                </div>

                <!-- Statistics Box -->
                <div class="bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-lg p-3 shadow-sm text-xs text-gray-500 dark:text-gray-400">
                    <div class="flex justify-between items-center py-1 border-b border-gray-100 dark:border-gray-800">
                        <span>Всього статей:</span>
                        <span id="statArticleCount" class="font-bold text-gray-800 dark:text-gray-200">0</span>
                    </div>
                    <div class="flex justify-between items-center py-1">
                        <span>Сховище:</span>
                        <span class="font-medium text-emerald-600 dark:text-emerald-400">LocalStorage</span>
                    </div>
                </div>

            </div>
        </aside>

        <!-- Center Content Main Window -->
        <main class="flex-1 min-w-0">
            
            <!-- Article Navigation Tabs (Читати / Редагувати / Вилучити / Історія) -->
            <div id="articleTabs" class="hidden flex items-center justify-between border-b border-gray-300 dark:border-gray-700 mb-4 pb-0">
                <div class="flex space-x-1 sm:space-x-2 -mb-px">
                    <button id="tabRead" onclick="app.switchTab('read')" class="px-3 sm:px-4 py-2 border-b-2 text-xs sm:text-sm font-medium flex items-center gap-1.5 transition-colors border-wikiblue text-wikiblue dark:text-wikiblue-dark">
                        <i class="fa-regular fa-file-lines"></i>
                        <span>Читати</span>
                    </button>
                    <button id="tabEdit" onclick="app.switchTab('edit')" class="px-3 sm:px-4 py-2 border-b-2 border-transparent text-xs sm:text-sm font-medium text-gray-500 hover:text-gray-700 dark:text-gray-400 dark:hover:text-gray-200 flex items-center gap-1.5 transition-colors">
                        <i class="fa-regular fa-pen-to-square"></i>
                        <span>Редагувати</span>
                    </button>
                    <button id="tabInfo" onclick="app.switchTab('info')" class="px-3 sm:px-4 py-2 border-b-2 border-transparent text-xs sm:text-sm font-medium text-gray-500 hover:text-gray-700 dark:text-gray-400 dark:hover:text-gray-200 flex items-center gap-1.5 transition-colors">
                        <i class="fa-solid fa-circle-info"></i>
                        <span>Інформація</span>
                    </button>
                </div>
                <div>
                    <button id="btnDeleteArticle" onclick="app.confirmDeleteArticle()" class="text-xs text-red-600 hover:text-red-700 dark:text-red-400 dark:hover:text-red-300 px-2 py-1 rounded hover:bg-red-50 dark:hover:bg-red-950/30 transition-colors flex items-center gap-1">
                        <i class="fa-regular fa-trash-can"></i>
                        <span class="hidden sm:inline">Вилучити</span>
                    </button>
                </div>
            </div>

            <!-- View Container 1: READ ARTICLE -->
            <div id="viewRead" class="bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-xl p-6 sm:p-8 shadow-sm relative min-h-[500px]">
                <div id="readContent">
                    <!-- Rendered content inserted here dynamically -->
                </div>
            </div>

            <!-- View Container 2: EDIT ARTICLE -->
            <div id="viewEdit" class="hidden bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-xl p-6 sm:p-8 shadow-sm">
                
                <h2 id="editHeaderTitle" class="wiki-heading text-2xl mb-6 pb-2 border-b border-gray-200 dark:border-gray-700 text-gray-800 dark:text-gray-100">
                    Редагування статті
                </h2>

                <form id="editForm" onsubmit="event.preventDefault(); app.saveArticle();" class="space-y-6">
                    
                    <!-- Article Title -->
                    <div>
                        <label class="block text-xs font-bold uppercase tracking-wider text-gray-600 dark:text-gray-400 mb-1">
                            Назва статті <span class="text-red-500">*</span>
                        </label>
                        <input type="text" id="editTitleInput" required
                               placeholder="Наприклад: Альберт Ейнштейн" 
                               class="w-full px-4 py-2.5 rounded-lg border border-gray-300 dark:border-gray-700 bg-gray-50 dark:bg-gray-900 text-gray-800 dark:text-gray-100 focus:outline-none focus:ring-2 focus:ring-wikiblue font-semibold text-lg">
                    </div>

                    <!-- Editor Formatting Toolbar -->
                    <div>
                        <div class="flex items-center justify-between mb-1">
                            <label class="block text-xs font-bold uppercase tracking-wider text-gray-600 dark:text-gray-400">
                                Текст статті (Wiki-синтаксис)
                            </label>
                            <span class="text-[11px] text-gray-400">Використовуйте [[Назва статті]] для внутрішніх посилань</span>
                        </div>
                        
                        <div class="border border-gray-300 dark:border-gray-700 rounded-lg overflow-hidden">
                            <!-- Toolbar buttons -->
                            <div class="bg-gray-100 dark:bg-gray-800 border-b border-gray-300 dark:border-gray-700 p-2 flex flex-wrap gap-1 text-sm">
                                <button type="button" onclick="app.insertFormat('h1')" title="Заголовок 1" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700 font-bold">H1</button>
                                <button type="button" onclick="app.insertFormat('h2')" title="Заголовок 2" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700 font-bold">H2</button>
                                <button type="button" onclick="app.insertFormat('bold')" title="Жирний" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700 font-bold"><i class="fa-solid fa-bold"></i></button>
                                <button type="button" onclick="app.insertFormat('italic')" title="Курсив" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700 italic"><i class="fa-solid fa-italic"></i></button>
                                <div class="h-5 w-px bg-gray-300 dark:bg-gray-600 my-auto mx-1"></div>
                                <button type="button" onclick="app.insertFormat('link')" title="Внутрішнє посилання [[Стаття]]" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700 text-wikiblue dark:text-wikiblue-dark"><i class="fa-solid fa-link"></i> [[Посилання]]</button>
                                <button type="button" onclick="app.insertFormat('list')" title="Маркований список" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700"><i class="fa-solid fa-list-ul"></i></button>
                                <button type="button" onclick="app.insertFormat('quote')" title="Цитата" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700"><i class="fa-solid fa-quote-left"></i></button>
                                <button type="button" onclick="app.insertFormat('image')" title="Зображення" class="px-2.5 py-1 rounded hover:bg-gray-200 dark:hover:bg-gray-700"><i class="fa-regular fa-image"></i></button>
                            </div>
                            
                            <!-- Textarea -->
                            <textarea id="editBodyInput" rows="16" required
                                      placeholder="Введіть вміст статті тут..."
                                      class="w-full p-4 bg-white dark:bg-gray-900 text-gray-800 dark:text-gray-100 font-mono text-sm leading-relaxed focus:outline-none resize-y"></textarea>
                        </div>
                    </div>

                    <!-- Infobox Constructor Section -->
                    <div class="border border-gray-200 dark:border-gray-800 rounded-lg p-4 bg-gray-50 dark:bg-gray-900/50 space-y-4">
                        <div class="flex justify-between items-center">
                            <div>
                                <h3 class="font-semibold text-sm text-gray-800 dark:text-gray-200 flex items-center gap-2">
                                    <i class="fa-solid fa-table-columns text-wikiblue"></i> Конструктор картки-інфобоксу (Infobox)
                                </h3>
                                <p class="text-xs text-gray-500">Інформаційна картка, що відображається праворуч у статті.</p>
                            </div>
                            <button type="button" onclick="app.toggleInfoboxSection()" id="btnToggleInfobox" class="text-xs text-wikiblue dark:text-wikiblue-dark font-medium hover:underline">
                                Сховати / Показати
                            </button>
                        </div>

                        <div id="infoboxFieldsContainer" class="space-y-3 pt-2">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-[11px] font-bold text-gray-500 uppercase mb-1">Заголовок картки</label>
                                    <input type="text" id="infoboxTitle" placeholder="Залиште порожнім для назви статті"
                                           class="w-full px-3 py-1.5 text-xs rounded border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-100">
                                </div>
                                <div>
                                    <label class="block text-[11px] font-bold text-gray-500 uppercase mb-1">URL фото / логотипу</label>
                                    <input type="url" id="infoboxImage" placeholder="https://example.com/photo.jpg"
                                           class="w-full px-3 py-1.5 text-xs rounded border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-100">
                                </div>
                            </div>

                            <div>
                                <label class="block text-[11px] font-bold text-gray-500 uppercase mb-1">Підпис до фото</label>
                                <input type="text" id="infoboxCaption" placeholder="Наприклад: Портрет, 1921 рік"
                                       class="w-full px-3 py-1.5 text-xs rounded border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-100">
                            </div>

                            <div>
                                <label class="block text-[11px] font-bold text-gray-500 uppercase mb-1 mb-2">Характеристики (Ключ - Значення)</label>
                                <div id="infoboxRows" class="space-y-2">
                                    <!-- Dynamic rows added here -->
                                </div>
                                <button type="button" onclick="app.addInfoboxRow()" class="mt-2 text-xs bg-gray-200 dark:bg-gray-800 hover:bg-gray-300 dark:hover:bg-gray-700 text-gray-700 dark:text-gray-300 font-medium px-3 py-1.5 rounded flex items-center gap-1 transition-colors">
                                    <i class="fa-solid fa-plus text-[10px]"></i> Додати рядок
                                </button>
                            </div>
                        </div>
                    </div>

                    <!-- Submit & Cancel Buttons -->
                    <div class="flex items-center gap-3 pt-2">
                        <button type="submit" class="bg-wikiblue hover:bg-blue-700 text-white font-medium text-sm px-6 py-2.5 rounded-lg shadow-sm transition-colors">
                            Зберегти сторінку
                        </button>
                        <button type="button" onclick="app.cancelEdit()" class="bg-gray-200 dark:bg-gray-800 hover:bg-gray-300 dark:hover:bg-gray-700 text-gray-700 dark:text-gray-300 text-sm font-medium px-5 py-2.5 rounded-lg transition-colors">
                            Скасувати
                        </button>
                    </div>

                </form>
            </div>

            <!-- View Container 3: ALL ARTICLES LIST -->
            <div id="viewAllArticles" class="hidden bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-xl p-6 sm:p-8 shadow-sm">
                <div class="flex flex-col sm:flex-row justify-between items-start sm:items-center gap-4 mb-6 pb-4 border-b border-gray-200 dark:border-gray-700">
                    <div>
                        <h2 class="wiki-heading text-2xl text-gray-800 dark:text-gray-100">Усі сторінки</h2>
                        <p class="text-xs text-gray-500 mt-1">Повний список створених статей у вашій персональній вікі.</p>
                    </div>
                    <button onclick="app.openNewArticleModal()" class="bg-wikiblue hover:bg-blue-700 text-white text-xs font-medium px-3 py-2 rounded-lg flex items-center gap-1.5">
                        <i class="fa-solid fa-plus"></i> Нова стаття
                    </button>
                </div>

                <div class="mb-4">
                    <input type="text" id="filterArticlesInput" oninput="app.renderArticlesList(this.value)" placeholder="Фільтр за назвою..."
                           class="w-full sm:w-72 px-3 py-2 text-sm rounded-lg border border-gray-300 dark:border-gray-700 bg-gray-50 dark:bg-gray-900 text-gray-800 dark:text-gray-100 focus:outline-none focus:ring-1 focus:ring-wikiblue">
                </div>

                <div id="allArticlesContainer" class="grid grid-cols-1 md:grid-cols-2 gap-3">
                    <!-- Dynamic List Cards -->
                </div>
            </div>

            <!-- View Container 4: BACKUP / IMPORT / EXPORT -->
            <div id="viewBackup" class="hidden bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-xl p-6 sm:p-8 shadow-sm">
                <h2 class="wiki-heading text-2xl mb-2 text-gray-800 dark:text-gray-100">Управління даними та Резервне копіювання</h2>
                <p class="text-xs text-gray-500 mb-6">Експортуйте або імпортуйте базу даних у форматі JSON для безпечного збереження чи перенесення на інший пристрій.</p>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <!-- Export Box -->
                    <div class="border border-gray-200 dark:border-gray-800 rounded-xl p-5 bg-gray-50 dark:bg-gray-900/40 flex flex-col justify-between">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-blue-100 dark:bg-blue-900/40 text-wikiblue dark:text-wikiblue-dark flex items-center justify-center text-lg mb-3">
                                <i class="fa-solid fa-file-export"></i>
                            </div>
                            <h3 class="font-semibold text-base mb-1 text-gray-800 dark:text-gray-200">Експорт бази даних</h3>
                            <p class="text-xs text-gray-500 dark:text-gray-400 mb-4 leading-relaxed">
                                Завантажте всі ваші статті та налаштування у вигляді єдиного `.json` файлу.
                            </p>
                        </div>
                        <button onclick="app.exportDatabase()" class="bg-wikiblue hover:bg-blue-700 text-white font-medium text-xs px-4 py-2.5 rounded-lg flex items-center justify-center gap-2 transition-colors">
                            <i class="fa-solid fa-download"></i> Завантажити JSON
                        </button>
                    </div>

                    <!-- Import Box -->
                    <div class="border border-gray-200 dark:border-gray-800 rounded-xl p-5 bg-gray-50 dark:bg-gray-900/40 flex flex-col justify-between">
                        <div>
                            <div class="w-10 h-10 rounded-lg bg-emerald-100 dark:bg-emerald-900/40 text-emerald-600 dark:text-emerald-400 flex items-center justify-center text-lg mb-3">
                                <i class="fa-solid fa-file-import"></i>
                            </div>
                            <h3 class="font-semibold text-base mb-1 text-gray-800 dark:text-gray-200">Імпорт з JSON</h3>
                            <p class="text-xs text-gray-500 dark:text-gray-400 mb-4 leading-relaxed">
                                Відновіть статті з раніше збереженого резервного JSON-файлу.
                            </p>
                        </div>
                        <div>
                            <input type="file" id="importFileInput" accept=".json" class="hidden" onchange="app.importDatabase(event)">
                            <button onclick="document.getElementById('importFileInput').click()" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-medium text-xs px-4 py-2.5 rounded-lg flex items-center justify-center gap-2 transition-colors">
                                <i class="fa-solid fa-upload"></i> Обрати файл JSON
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Danger Zone Reset -->
                <div class="mt-8 pt-6 border-t border-gray-200 dark:border-gray-800">
                    <h4 class="text-xs font-bold uppercase tracking-wider text-red-600 dark:text-red-400 mb-2">Небезпечно</h4>
                    <div class="flex flex-col sm:flex-row items-start sm:items-center justify-between gap-4 p-4 border border-red-200 dark:border-red-900/50 bg-red-50/50 dark:bg-red-950/20 rounded-lg">
                        <div>
                            <div class="font-semibold text-xs text-gray-800 dark:text-gray-200">Очистити всю базу даних</div>
                            <div class="text-[11px] text-gray-500">Вилучить абсолютно всі збережені статті з LocalStorage.</div>
                        </div>
                        <button onclick="app.confirmResetAll()" class="bg-red-600 hover:bg-red-700 text-white font-medium text-xs px-3.5 py-2 rounded transition-colors flex items-center gap-1.5">
                            <i class="fa-solid fa-trash"></i> Очистити базу
                        </button>
                    </div>
                </div>
            </div>

            <!-- View Container 5: ARTICLE INFO / METADATA -->
            <div id="viewInfo" class="hidden bg-white dark:bg-[#1c2128] border border-gray-200 dark:border-gray-800 rounded-xl p-6 sm:p-8 shadow-sm">
                <h2 class="wiki-heading text-2xl mb-4 text-gray-800 dark:text-gray-100 border-b border-gray-200 dark:border-gray-700 pb-2">
                    Інформація про сторінку
                </h2>
                <div id="infoMetaContent" class="space-y-4 text-xs sm:text-sm">
                    <!-- Populated dynamically -->
                </div>
            </div>

        </main>
    </div>

    <!-- Custom Modal Dialog (Replaces native alert/confirm) -->
    <div id="customModal" class="hidden fixed inset-0 z-50 flex items-center justify-center bg-black/50 p-4 backdrop-blur-sm">
        <div class="bg-white dark:bg-[#22272e] rounded-xl border border-gray-200 dark:border-gray-700 shadow-2xl max-w-md w-full overflow-hidden transform transition-all">
            <div class="p-6">
                <div class="flex items-center gap-3 mb-3">
                    <div id="modalIconContainer" class="w-9 h-9 rounded-full flex items-center justify-center bg-blue-100 dark:bg-blue-900/50 text-wikiblue">
                        <i id="modalIcon" class="fa-solid fa-circle-info text-base"></i>
                    </div>
                    <h3 id="modalTitle" class="font-bold text-lg text-gray-900 dark:text-gray-100">Заголовок</h3>
                </div>
                <p id="modalMessage" class="text-xs sm:text-sm text-gray-600 dark:text-gray-300 leading-relaxed">
                    Повідомлення моделі...
                </p>
                <div id="modalCustomInputContainer" class="hidden mt-4">
                    <input type="text" id="modalInput" class="w-full px-3 py-2 text-sm rounded border border-gray-300 dark:border-gray-700 bg-gray-50 dark:bg-gray-800 text-gray-800 dark:text-gray-100 focus:outline-none focus:ring-2 focus:ring-wikiblue">
                </div>
            </div>
            <div class="bg-gray-50 dark:bg-[#1c2128] px-6 py-3 border-t border-gray-200 dark:border-gray-800 flex justify-end gap-2">
                <button id="modalCancelBtn" onclick="app.closeModal(false)" class="px-4 py-1.5 text-xs font-medium rounded-lg bg-gray-200 dark:bg-gray-800 text-gray-700 dark:text-gray-300 hover:bg-gray-300 dark:hover:bg-gray-700 transition-colors">
                    Скасувати
                </button>
                <button id="modalConfirmBtn" onclick="app.closeModal(true)" class="px-4 py-1.5 text-xs font-medium rounded-lg bg-wikiblue text-white hover:bg-blue-700 transition-colors">
                    Підтвердити
                </button>
            </div>
        </div>
    </div>

    <!-- Toast Notification -->
    <div id="toastNotification" class="fixed bottom-5 right-5 z-50 transform translate-y-20 opacity-0 transition-all duration-300 pointer-events-none">
        <div class="bg-gray-900 text-white dark:bg-white dark:text-gray-900 px-4 py-3 rounded-lg shadow-2xl text-xs sm:text-sm font-medium flex items-center gap-2.5">
            <i id="toastIcon" class="fa-solid fa-circle-check text-emerald-400 dark:text-emerald-600"></i>
            <span id="toastMessage">Сповіщення</span>
        </div>
    </div>

    <script>
        /**
         * Main Personal Wiki Application Logic
         */
        class WikiApp {
            constructor() {
                // Constants
                this.STORAGE_KEY = 'personal_wiki_articles_v2';
                this.THEME_KEY = 'personal_wiki_theme';
                this.HOME_TITLE = 'Головна сторінка';

                // Initial State
                this.articles = {};
                this.currentTitle = this.HOME_TITLE;
                this.currentTab = 'read'; // 'read', 'edit', 'info'
                this.modalCallback = null;

                // Load Initial Storage & Theme
                this.initTheme();
                this.loadArticles();
                this.ensureHomePageExists();

                // Setup Listeners
                this.setupEventListeners();
                
                // Render initial page
                this.navigateTo(this.HOME_TITLE);
            }

            /* --- STORAGE MANAGERS --- */
            loadArticles() {
                try {
                    const raw = localStorage.getItem(this.STORAGE_KEY);
                    if (raw) {
                        this.articles = JSON.parse(raw);
                    } else {
                        this.articles = {};
                    }
                } catch (e) {
                    console.error("Failed to load articles from localStorage", e);
                    this.articles = {};
                }
            }

            saveArticles() {
                try {
                    localStorage.setItem(this.STORAGE_KEY, JSON.stringify(this.articles));
                    this.updateSidebarStats();
                } catch (e) {
                    this.showToast('Помилка збереження в LocalStorage!', 'error');
                }
            }

            /* --- CLEAN HOMEPAGE INITIALIZER --- */
            ensureHomePageExists() {
                // Clean requirement: Homepage strictly has instructions on how to start, NO fake articles.
                if (!this.articles[this.HOME_TITLE]) {
                    this.articles[this.HOME_TITLE] = {
                        title: this.HOME_TITLE,
                        body: `Ласкаво просимо до вашої **Персональної Вікіпедії**!

Це чистий, автономний вікі-сайт у стилі MediaWiki для впорядкування власних нотаток, знань та матеріалів.

== Як розпочати роботу? ==

* **Створити першу статтю:** Натисніть синю кнопку **«+ Створити»** у верхньому меню.
* **Внутрішні посилання:** Під час написання статей використовуйте подвійні квадратні дужки: \`[[Назва статті]]\`.
  * Якщо стаття з такою назвою вже існує — посилання буде [[синім]].
  * Якщо статті ще немає — посилання буде [[Червоним]], і клік по ньому одразу створить нову сторінку!
* **Картка-Інфобокс:** Під час редагування заповнюйте таблицю "Інфобокс", щоб додати красиву картку з характеристиками справа від тексту.
* **Резервне копіювання:** Усі ваші дані зберігаються у браузері (LocalStorage). Ви можете у будь-який момент експортувати їх у JSON-файл у розділі [[Експорт / Імпорт]].

== Основні можливості ==

# **Швидкий пошук** з автодоповненням у шапці сайту.
# **Підтримка темної та світлої тем** (перемикач у правому верхньому кутку).
# **Генерація Змісту (TOC)** для статей із заголовками.
# **Випадкова стаття** для зручного перегляду.`,
                        infobox: {
                            title: "Ласкаво просимо",
                            image: "",
                            caption: "Ваша особиста енциклопедія",
                            data: [
                                { key: "Тип", value: "Особиста Вікі" },
                                { key: "Формат", value: "MediaWiki Style" },
                                { key: "Збереження", value: "LocalStorage / JSON" }
                            ]
                        },
                        createdAt: new Date().toISOString(),
                        updatedAt: new Date().toISOString()
                    };
                    this.saveArticles();
                }
            }

            /* --- THEME HANDLING --- */
            initTheme() {
                const savedTheme = localStorage.getItem(this.THEME_KEY) || 'light';
                if (savedTheme === 'dark') {
                    document.documentElement.classList.add('dark');
                } else {
                    document.documentElement.classList.remove('dark');
                }
            }

            toggleTheme() {
                const isDark = document.documentElement.classList.toggle('dark');
                localStorage.setItem(this.THEME_KEY, isDark ? 'dark' : 'light');
                this.showToast(isDark ? 'Увімкнено темну тему' : 'Увімкнено світлу тему');
            }

            /* --- EVENT LISTENERS --- */
            setupEventListeners() {
                // Sidebar Toggle
                document.getElementById('sidebarToggleBtn').addEventListener('click', () => {
                    const sidebar = document.getElementById('sidebar');
                    sidebar.classList.toggle('hidden');
                });

                // Click outside search results to hide
                document.addEventListener('click', (e) => {
                    const searchBox = document.getElementById('searchResults');
                    const searchInput = document.getElementById('searchInput');
                    if (!searchBox.contains(e.target) && !searchInput.contains(e.target)) {
                        searchBox.classList.add('hidden');
                    }
                });
            }

            /* --- NAVIGATION & VIEW MODES --- */
            navigateTo(title) {
                if (!title) return;
                this.currentTitle = title;
                
                // If article exists, view read mode; if not, suggest creating
                if (this.articles[title]) {
                    this.switchTab('read');
                } else {
                    this.openCreateMissingArticleModal(title);
                }

                this.updateSidebarStats();
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }

            goHome() {
                this.navigateTo(this.HOME_TITLE);
            }

            switchTab(tab) {
                this.currentTab = tab;
                const viewRead = document.getElementById('viewRead');
                const viewEdit = document.getElementById('viewEdit');
                const viewInfo = document.getElementById('viewInfo');
                const viewAllArticles = document.getElementById('viewAllArticles');
                const viewBackup = document.getElementById('viewBackup');
                const articleTabs = document.getElementById('articleTabs');

                // Hide special views
                viewAllArticles.classList.add('hidden');
                viewBackup.classList.add('hidden');
                articleTabs.classList.remove('hidden');

                // Update Tab styling
                ['Read', 'Edit', 'Info'].forEach(t => {
                    const btn = document.getElementById(`tab${t}`);
                    if (t.toLowerCase() === tab) {
                        btn.className = "px-3 sm:px-4 py-2 border-b-2 border-wikiblue text-wikiblue dark:text-wikiblue-dark text-xs sm:text-sm font-semibold flex items-center gap-1.5 transition-colors";
                    } else {
                        btn.className = "px-3 sm:px-4 py-2 border-b-2 border-transparent text-gray-500 hover:text-gray-700 dark:text-gray-400 dark:hover:text-gray-200 text-xs sm:text-sm font-medium flex items-center gap-1.5 transition-colors";
                    }
                });

                // Toggle visibility
                viewRead.classList.toggle('hidden', tab !== 'read');
                viewEdit.classList.toggle('hidden', tab !== 'edit');
                viewInfo.classList.toggle('hidden', tab !== 'info');

                if (tab === 'read') {
                    this.renderReadView();
                } else if (tab === 'edit') {
                    this.renderEditView();
                } else if (tab === 'info') {
                    this.renderInfoView();
                }
            }

            showAllArticles() {
                document.getElementById('articleTabs').classList.add('hidden');
                document.getElementById('viewRead').classList.add('hidden');
                document.getElementById('viewEdit').classList.add('hidden');
                document.getElementById('viewInfo').classList.add('hidden');
                document.getElementById('viewBackup').classList.add('hidden');
                document.getElementById('viewAllArticles').classList.remove('hidden');
                
                this.renderArticlesList();
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }

            showBackupView() {
                document.getElementById('articleTabs').classList.add('hidden');
                document.getElementById('viewRead').classList.add('hidden');
                document.getElementById('viewEdit').classList.add('hidden');
                document.getElementById('viewInfo').classList.add('hidden');
                document.getElementById('viewAllArticles').classList.add('hidden');
                document.getElementById('viewBackup').classList.remove('hidden');
                
                window.scrollTo({ top: 0, behavior: 'smooth' });
            }

            openRandomArticle() {
                const keys = Object.keys(this.articles);
                if (keys.length === 0) {
                    this.showToast('Немає створених статей', 'info');
                    return;
                }
                const randomTitle = keys[Math.floor(Math.random() * keys.length)];
                this.navigateTo(randomTitle);
            }

            /* --- WIKITEXT PARSER ENGINE --- */
            parseWikitext(text) {
                if (!text) return '';

                let html = text;

                // Escape raw HTML tags for safety
                html = html.replace(/</g, '&lt;').replace(/>/g, '&gt;');

                // Headings parsing: == Heading 1 == or === Heading 2 ===
                const headings = [];
                html = html.replace(/^===\s*(.*?)\s*===$/gm, (match, p1) => {
                    const id = 'heading-' + Math.random().toString(36).substr(2, 6);
                    headings.push({ level: 3, text: p1, id });
                    return `<h3 id="${id}">${p1}</h3>`;
                });

                html = html.replace(/^==\s*(.*?)\s*==$/gm, (match, p1) => {
                    const id = 'heading-' + Math.random().toString(36).substr(2, 6);
                    headings.push({ level: 2, text: p1, id });
                    return `<h2 id="${id}">${p1}</h2>`;
                });

                html = html.replace(/^=\s*(.*?)\s*=$/gm, (match, p1) => {
                    const id = 'heading-' + Math.random().toString(36).substr(2, 6);
                    headings.push({ level: 1, text: p1, id });
                    return `<h1 id="${id}">${p1}</h1>`;
                });

                // Bold: '''text''' or **text**
                html = html.replace(/(\'''|\*\*)\s*(.*?)\s*(\'''|\*\*)/g, '<strong>$2</strong>');

                // Italic: ''text'' or *text*
                html = html.replace(/(\''|\*)\s*(.*?)\s*(\''|\*)/g, '<em>$2</em>');

                // Blockquotes: > quote
                html = html.replace(/^&gt;\s*(.*)$/gm, '<blockquote>$1</blockquote>');

                // Unordered Lists: * item or - item
                html = html.replace(/^[\*\-]\s+(.*)$/gm, '<ul><li>$1</li></ul>');
                html = html.replace(/<\/ul>\s*<ul>/g, ''); // Join adjacent ul tags

                // Ordered Lists: # item or 1. item
                html = html.replace(/^(\#|\d+\.)\s+(.*)$/gm, '<ol><li>$2</li></ol>');
                html = html.replace(/<\/ol>\s*<ol>/g, ''); // Join adjacent ol tags

                // Images syntax: [[Файл:URL|Підпис]] or [[File:URL|Caption]]
                html = html.replace(/\[\[(Файл|File):([^\|\]]+)(?:\|([^\]]+))?\]\]/gi, (match, prefix, url, caption) => {
                    const capText = caption ? `<div class="text-[11px] text-gray-500 dark:text-gray-400 mt-1 text-center">${caption}</div>` : '';
                    return `<div class="article-img-container rounded shadow-sm">
                        <img src="${url.trim()}" alt="${caption || 'Зображення'}" class="max-w-full h-auto rounded" onerror="this.src='https://placehold.co/300x200/e2e8f0/64748b?text=Помилка+фото'">
                        ${capText}
                    </div>`;
                });

                // Internal Links: [[Назва статті]] or [[Назва статті|Відображуваний текст]]
                html = html.replace(/\[\[([^\]\|]+)(?:\|([^\]]+))?\]\]/g, (match, target, display) => {
                    const cleanTarget = target.trim();
                    const textDisplay = (display || target).trim();
                    
                    const exists = !!this.articles[cleanTarget];
                    if (exists) {
                        return `<a href="javascript:void(0)" onclick="app.navigateTo('${cleanTarget.replace(/'/g, "\\'")}')" class="wiki-link-exist">${textDisplay}</a>`;
                    } else {
                        return `<a href="javascript:void(0)" onclick="app.navigateTo('${cleanTarget.replace(/'/g, "\\'")}')" class="wiki-link-missing" title="Сторінки «${cleanTarget}» ще не існує. Натисніть, щоб створити.">${textDisplay}</a>`;
                    }
                });

                // Paragraphs formatting (newlines)
                const paragraphs = html.split(/\n\n+/);
                html = paragraphs.map(p => {
                    p = p.trim();
                    if (!p) return '';
                    if (p.startsWith('<h') || p.startsWith('<ul') || p.startsWith('<ol') || p.startsWith('<blockquote') || p.startsWith('<div')) {
                        return p;
                    }
                    return `<p>${p.replace(/\n/g, '<br>')}</p>`;
                }).join('\n');

                return { html, headings };
            }

            /* --- RENDER READ VIEW --- */
            renderReadView() {
                const article = this.articles[this.currentTitle];
                const readContent = document.getElementById('readContent');

                if (!article) {
                    readContent.innerHTML = `
                        <div class="text-center py-12">
                            <div class="w-16 h-16 mx-auto mb-4 rounded-full bg-red-100 dark:bg-red-950/40 text-red-500 flex items-center justify-center text-2xl">
                                <i class="fa-solid fa-file-circle-xmark"></i>
                            </div>
                            <h2 class="text-xl font-bold mb-2">Сторінку «${this.escapeHtml(this.currentTitle)}» не знайдено</h2>
                            <p class="text-xs text-gray-500 mb-6">Ви можете створити статтю з такою назвою прямо зараз.</p>
                            <button onclick="app.createNewArticleNamed('${this.escapeHtml(this.currentTitle)}')" class="bg-wikiblue hover:bg-blue-700 text-white font-medium text-xs px-4 py-2 rounded-lg transition-colors">
                                <i class="fa-solid fa-pen-to-square mr-1"></i> Створити статтю
                            </button>
                        </div>
                    `;
                    return;
                }

                // Parse body text
                const { html: parsedBody, headings } = this.parseWikitext(article.body);

                // Build Table of Contents HTML if >= 2 headings exist
                let tocHtml = '';
                if (headings.length >= 2) {
                    tocHtml = `
                        <div class="my-4 border border-gray-200 dark:border-gray-700 bg-gray-50 dark:bg-gray-800/60 rounded-lg p-3 max-w-xs text-xs">
                            <div class="font-bold text-gray-700 dark:text-gray-300 mb-2 flex items-center gap-1.5 border-b border-gray-200 dark:border-gray-700 pb-1">
                                <i class="fa-solid fa-list-ol text-wikiblue"></i> Зміст
                            </div>
                            <ul class="space-y-1">
                                ${headings.map((h, index) => `
                                    <li style="margin-left: ${(h.level - 1) * 12}px">
                                        <a href="#${h.id}" class="text-wikiblue dark:text-wikiblue-dark hover:underline flex gap-1">
                                            <span class="text-gray-400 font-mono">${index + 1}.</span>
                                            <span>${this.escapeHtml(h.text)}</span>
                                        </a>
                                    </li>
                                `).join('')}
                            </ul>
                        </div>
                    `;
                }

                // Render Infobox if present
                let infoboxHtml = '';
                if (article.infobox && (article.infobox.title || article.infobox.image || (article.infobox.data && article.infobox.data.length > 0))) {
                    const info = article.infobox;
                    infoboxHtml = `
                        <div class="w-full md:w-80 md:float-right md:ml-6 mb-6 border border-wikiborder-light dark:border-wikiborder-dark bg-gray-50 dark:bg-[#22272e] rounded-lg overflow-hidden shadow-sm">
                            <div class="bg-gray-200 dark:bg-gray-800 p-2.5 text-center border-b border-gray-300 dark:border-gray-700 font-bold text-sm wiki-heading text-gray-800 dark:text-gray-100">
                                ${this.escapeHtml(info.title || article.title)}
                            </div>
                            ${info.image ? `
                                <div class="p-3 border-b border-gray-200 dark:border-gray-700 text-center bg-white dark:bg-gray-900">
                                    <img src="${info.image}" alt="Infobox Photo" class="max-w-full h-auto max-h-64 mx-auto rounded shadow-sm" onerror="this.src='https://placehold.co/400x300/e2e8f0/64748b?text=Зображення'">
                                    ${info.caption ? `<div class="text-[11px] text-gray-500 dark:text-gray-400 mt-1.5 italic">${this.escapeHtml(info.caption)}</div>` : ''}
                                </div>
                            ` : ''}
                            ${info.data && info.data.length > 0 ? `
                                <table class="w-full text-xs">
                                    <tbody>
                                        ${info.data.map(row => `
                                            <tr class="border-b border-gray-200 dark:border-gray-800 last:border-0">
                                                <th class="py-2 px-3 text-left font-semibold text-gray-600 dark:text-gray-400 bg-gray-100/70 dark:bg-gray-800/50 w-1/3 border-r border-gray-200 dark:border-gray-800">
                                                    ${this.escapeHtml(row.key)}
                                                </th>
                                                <td class="py-2 px-3 text-gray-800 dark:text-gray-200">
                                                    ${this.escapeHtml(row.value)}
                                                </td>
                                            </tr>
                                        `).join('')}
                                    </tbody>
                                </table>
                            ` : ''}
                        </div>
                    `;
                }

                // Inject final page structure
                readContent.innerHTML = `
                    <div class="flex items-baseline justify-between border-b border-gray-300 dark:border-gray-700 pb-2 mb-4">
                        <h1 class="wiki-heading text-3xl font-normal text-gray-900 dark:text-gray-50">
                            ${this.escapeHtml(article.title)}
                        </h1>
                        <span class="text-[11px] text-gray-400 hidden sm:inline">Матеріал з Вікіпедії — вільної енциклопедії</span>
                    </div>

                    ${infoboxHtml}

                    ${tocHtml}

                    <div class="article-body text-sm sm:text-base leading-relaxed text-slate-800 dark:text-slate-200">
                        ${parsedBody}
                    </div>

                    <div class="clear-both mt-12 pt-4 border-t border-gray-200 dark:border-gray-800 text-xs text-gray-400 flex flex-wrap justify-between items-center gap-2">
                        <div>
                            Останнє редагування: ${new Date(article.updatedAt).toLocaleString('uk-UA')}
                        </div>
                        <div class="flex items-center gap-1 text-gray-500">
                            <i class="fa-solid fa-tag"></i> Категорія: <span class="text-wikiblue dark:text-wikiblue-dark">Вікі-статті</span>
                        </div>
                    </div>
                `;
            }

            /* --- RENDER EDIT VIEW --- */
            renderEditView() {
                const article = this.articles[this.currentTitle] || {
                    title: this.currentTitle,
                    body: '',
                    infobox: { title: '', image: '', caption: '', data: [] }
                };

                document.getElementById('editHeaderTitle').innerText = this.articles[this.currentTitle] 
                    ? `Редагування сторінки «${article.title}»` 
                    : `Створення нової статті «${article.title}»`;

                document.getElementById('editTitleInput').value = article.title;
                document.getElementById('editBodyInput').value = article.body;

                // Load Infobox
                const info = article.infobox || {};
                document.getElementById('infoboxTitle').value = info.title || '';
                document.getElementById('infoboxImage').value = info.image || '';
                document.getElementById('infoboxCaption').value = info.caption || '';

                const rowsContainer = document.getElementById('infoboxRows');
                rowsContainer.innerHTML = '';

                if (info.data && info.data.length > 0) {
                    info.data.forEach(row => this.addInfoboxRow(row.key, row.value));
                } else {
                    // Default empty row
                    this.addInfoboxRow();
                }
            }

            addInfoboxRow(key = '', value = '') {
                const rowsContainer = document.getElementById('infoboxRows');
                const rowId = 'info-row-' + Math.random().toString(36).substr(2, 6);
                
                const rowDiv = document.createElement('div');
                rowDiv.id = rowId;
                rowDiv.className = 'flex items-center gap-2';
                rowDiv.innerHTML = `
                    <input type="text" placeholder="Ключ (напр. Засновано)" value="${this.escapeHtml(key)}"
                           class="infobox-key w-1/2 px-2.5 py-1 text-xs rounded border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-100">
                    <input type="text" placeholder="Значення (напр. 1991 рік)" value="${this.escapeHtml(value)}"
                           class="infobox-value w-1/2 px-2.5 py-1 text-xs rounded border border-gray-300 dark:border-gray-700 bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-100">
                    <button type="button" onclick="document.getElementById('${rowId}').remove()" class="text-red-500 hover:text-red-700 p-1 text-xs" title="Вилучити рядок">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                `;
                rowsContainer.appendChild(rowDiv);
            }

            toggleInfoboxSection() {
                const container = document.getElementById('infoboxFieldsContainer');
                container.classList.toggle('hidden');
            }

            insertFormat(type) {
                const textarea = document.getElementById('editBodyInput');
                const start = textarea.selectionStart;
                const end = textarea.selectionEnd;
                const selected = textarea.value.substring(start, end);

                let replacement = '';
                switch (type) {
                    case 'h1':
                        replacement = `== ${selected || 'Заголовок'} ==`;
                        break;
                    case 'h2':
                        replacement = `=== ${selected || 'Підзаголовок'} ===`;
                        break;
                    case 'bold':
                        replacement = `'''${selected || 'Жирний текст'}'''`;
                        break;
                    case 'italic':
                        replacement = `''${selected || 'Курсивний текст'}''`;
                        break;
                    case 'link':
                        replacement = `[[${selected || 'Назва статті'}]]`;
                        break;
                    case 'list':
                        replacement = `* ${selected || 'Елемент списка'}`;
                        break;
                    case 'quote':
                        replacement = `> ${selected || 'Цитата'}`;
                        break;
                    case 'image':
                        replacement = `[[Файл:https://example.com/image.jpg|Підпис зображення]]`;
                        break;
                }

                textarea.value = textarea.value.substring(0, start) + replacement + textarea.value.substring(end);
                textarea.focus();
            }

            saveArticle() {
                const newTitle = document.getElementById('editTitleInput').value.trim();
                const body = document.getElementById('editBodyInput').value;

                if (!newTitle) {
                    this.showToast('Введіть назву статті', 'error');
                    return;
                }

                // Gather Infobox Data
                const infoTitle = document.getElementById('infoboxTitle').value.trim();
                const infoImage = document.getElementById('infoboxImage').value.trim();
                const infoCaption = document.getElementById('infoboxCaption').value.trim();

                const keys = document.querySelectorAll('.infobox-key');
                const values = document.querySelectorAll('.infobox-value');
                const infoboxData = [];

                keys.forEach((keyEl, index) => {
                    const k = keyEl.value.trim();
                    const v = values[index] ? values[index].value.trim() : '';
                    if (k) {
                        infoboxData.push({ key: k, value: v });
                    }
                });

                // Check if title was changed during editing
                if (this.currentTitle !== newTitle && this.articles[this.currentTitle]) {
                    delete this.articles[this.currentTitle];
                }

                const now = new Date().toISOString();
                const existing = this.articles[newTitle];

                this.articles[newTitle] = {
                    title: newTitle,
                    body: body,
                    infobox: {
                        title: infoTitle,
                        image: infoImage,
                        caption: infoCaption,
                        data: infoboxData
                    },
                    createdAt: existing ? existing.createdAt : now,
                    updatedAt: now
                };

                this.saveArticles();
                this.currentTitle = newTitle;
                this.showToast('Статтю успішно збережено!');
                this.switchTab('read');
            }

            cancelEdit() {
                this.switchTab('read');
            }

            /* --- RENDER INFO / METADATA VIEW --- */
            renderInfoView() {
                const article = this.articles[this.currentTitle];
                const infoMetaContent = document.getElementById('infoMetaContent');

                if (!article) {
                    infoMetaContent.innerHTML = '<p class="text-gray-500">Інформація недоступна.</p>';
                    return;
                }

                const wordCount = article.body.trim() ? article.body.trim().split(/\s+/).length : 0;
                const charCount = article.body.length;

                infoMetaContent.innerHTML = `
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="p-4 border border-gray-200 dark:border-gray-800 rounded-lg bg-gray-50 dark:bg-gray-900/50">
                            <span class="text-gray-400 block mb-1">Назва сторінки</span>
                            <span class="font-bold text-gray-800 dark:text-gray-200 text-base">${this.escapeHtml(article.title)}</span>
                        </div>
                        <div class="p-4 border border-gray-200 dark:border-gray-800 rounded-lg bg-gray-50 dark:bg-gray-900/50">
                            <span class="text-gray-400 block mb-1">Дата створення</span>
                            <span class="font-medium text-gray-800 dark:text-gray-200">${new Date(article.createdAt).toLocaleString('uk-UA')}</span>
                        </div>
                        <div class="p-4 border border-gray-200 dark:border-gray-800 rounded-lg bg-gray-50 dark:bg-gray-900/50">
                            <span class="text-gray-400 block mb-1">Кількість слів</span>
                            <span class="font-bold text-wikiblue dark:text-wikiblue-dark">${wordCount}</span>
                        </div>
                        <div class="p-4 border border-gray-200 dark:border-gray-800 rounded-lg bg-gray-50 dark:bg-gray-900/50">
                            <span class="text-gray-400 block mb-1">Символів усього</span>
                            <span class="font-bold text-emerald-600 dark:text-emerald-400">${charCount}</span>
                        </div>
                    </div>
                `;
            }

            confirmDeleteArticle() {
                if (this.currentTitle === this.HOME_TITLE) {
                    this.showToast('Головну сторінку не можна вилучити!', 'error');
                    return;
                }

                this.openModal({
                    title: 'Вилучення статті',
                    message: `Ви дійсно бажаєте остаточно вилучити статтю «${this.currentTitle}»? Цю дію неможливо скасувати.`,
                    icon: 'fa-triangle-exclamation',
                    iconClass: 'bg-red-100 text-red-600 dark:bg-red-950/50',
                    confirmText: 'Так, вилучити',
                    onConfirm: () => {
                        delete this.articles[this.currentTitle];
                        this.saveArticles();
                        this.showToast(`Статтю «${this.currentTitle}» вилучено`);
                        this.goHome();
                    }
                });
            }

            deleteSpecificArticle(title) {
                if (title === this.HOME_TITLE) {
                    this.showToast('Головну сторінку не можна вилучити!', 'error');
                    return;
                }

                this.openModal({
                    title: 'Вилучення статті',
                    message: `Вилучити статтю «${title}»?`,
                    icon: 'fa-trash',
                    iconClass: 'bg-red-100 text-red-600 dark:bg-red-950/50',
                    confirmText: 'Вилучити',
                    onConfirm: () => {
                        delete this.articles[title];
                        this.saveArticles();
                        this.showToast(`Статтю «${title}» вилучено`);
                        if (this.currentTitle === title) {
                            this.goHome();
                        } else {
                            this.renderArticlesList();
                        }
                    }
                });
            }

            /* --- ALL ARTICLES GRID --- */
            renderArticlesList(filterQuery = '') {
                const container = document.getElementById('allArticlesContainer');
                const query = filterQuery.toLowerCase().trim();
                const keys = Object.keys(this.articles).sort();

                const filtered = keys.filter(key => key.toLowerCase().includes(query));

                if (filtered.length === 0) {
                    container.innerHTML = `
                        <div class="col-span-full py-8 text-center text-gray-400 text-xs">
                            Жодної статті не знайдено за вашим запитом.
                        </div>
                    `;
                    return;
                }

                container.innerHTML = filtered.map(title => {
                    const art = this.articles[title];
                    const isHome = title === this.HOME_TITLE;
                    const dateStr = new Date(art.updatedAt).toLocaleDateString('uk-UA');

                    return `
                        <div class="border border-gray-200 dark:border-gray-800 rounded-lg p-4 bg-gray-50/50 dark:bg-gray-900/30 hover:border-wikiblue transition-colors flex justify-between items-center gap-3">
                            <div class="min-w-0">
                                <a href="javascript:void(0)" onclick="app.navigateTo('${this.escapeHtml(title)}')" class="font-bold text-sm text-wikiblue dark:text-wikiblue-dark hover:underline truncate block">
                                    ${this.escapeHtml(title)}
                                </a>
                                <div class="text-[11px] text-gray-400 mt-0.5">
                                    Оновлено: ${dateStr}
                                </div>
                            </div>
                            <div class="flex items-center gap-1">
                                <button onclick="app.navigateTo('${this.escapeHtml(title)}')" class="p-1.5 text-gray-500 hover:text-wikiblue rounded" title="Читати">
                                    <i class="fa-regular fa-eye text-xs"></i>
                                </button>
                                ${!isHome ? `
                                    <button onclick="app.deleteSpecificArticle('${this.escapeHtml(title)}')" class="p-1.5 text-gray-400 hover:text-red-500 rounded" title="Вилучити">
                                        <i class="fa-regular fa-trash-can text-xs"></i>
                                    </button>
                                ` : ''}
                            </div>
                        </div>
                    `;
                }).join('');
            }

            /* --- SEARCH FUNCTIONALITY --- */
            handleSearchInput(value) {
                const resultsContainer = document.getElementById('searchResults');
                const clearBtn = document.getElementById('clearSearchBtn');

                if (!value.trim()) {
                    resultsContainer.classList.add('hidden');
                    clearBtn.classList.add('hidden');
                    return;
                }

                clearBtn.classList.remove('hidden');
                const query = value.toLowerCase().trim();
                const matches = Object.keys(this.articles).filter(title => title.toLowerCase().includes(query));

                if (matches.length === 0) {
                    resultsContainer.innerHTML = `
                        <div class="p-3 text-xs text-gray-500">
                            Статтю не знайдено. <a href="javascript:void(0)" onclick="app.createNewArticleNamed('${this.escapeHtml(value)}')" class="text-wikiblue dark:text-wikiblue-dark hover:underline font-semibold">Створити «${this.escapeHtml(value)}»?</a>
                        </div>
                    `;
                } else {
                    resultsContainer.innerHTML = matches.map(title => `
                        <a href="javascript:void(0)" onclick="app.selectSearchResult('${this.escapeHtml(title)}')" 
                           class="block px-4 py-2 text-xs sm:text-sm text-gray-800 dark:text-gray-200 hover:bg-gray-100 dark:hover:bg-gray-800 transition-colors flex items-center gap-2">
                            <i class="fa-regular fa-file-lines text-wikiblue"></i>
                            <span>${this.escapeHtml(title)}</span>
                        </a>
                    `).join('');
                }

                resultsContainer.classList.remove('hidden');
            }

            handleSearchKeyUp(event) {
                if (event.key === 'Enter') {
                    const value = event.target.value.trim();
                    if (value) {
                        document.getElementById('searchResults').classList.add('hidden');
                        this.navigateTo(value);
                    }
                }
            }

            selectSearchResult(title) {
                document.getElementById('searchResults').classList.add('hidden');
                document.getElementById('searchInput').value = '';
                document.getElementById('clearSearchBtn').classList.add('hidden');
                this.navigateTo(title);
            }

            clearSearch() {
                document.getElementById('searchInput').value = '';
                document.getElementById('searchResults').classList.add('hidden');
                document.getElementById('clearSearchBtn').classList.add('hidden');
            }

            /* --- SIDEBAR RECENT & STATS --- */
            updateSidebarStats() {
                const keys = Object.keys(this.articles);
                document.getElementById('statArticleCount').innerText = keys.length;

                const recentList = document.getElementById('recentArticlesList');
                const sorted = [...keys].sort((a, b) => new Date(this.articles[b].updatedAt) - new Date(this.articles[a].updatedAt)).slice(0, 5);

                recentList.innerHTML = sorted.map(title => `
                    <li>
                        <a href="javascript:void(0)" onclick="app.navigateTo('${this.escapeHtml(title)}')" 
                           class="block px-2 py-1 rounded text-gray-600 dark:text-gray-300 hover:bg-gray-100 dark:hover:bg-gray-800 hover:text-wikiblue dark:hover:text-wikiblue-dark truncate transition-colors">
                            ${this.escapeHtml(title)}
                        </a>
                    </li>
                `).join('');
            }

            /* --- EXPORT / IMPORT JSON --- */
            exportDatabase() {
                const dataStr = "data:text/json;charset=utf-8," + encodeURIComponent(JSON.stringify(this.articles, null, 2));
                const downloadAnchor = document.createElement('a');
                downloadAnchor.setAttribute("href", dataStr);
                downloadAnchor.setAttribute("download", `wiki_backup_${new Date().toISOString().slice(0, 10)}.json`);
                document.body.appendChild(downloadAnchor);
                downloadAnchor.click();
                downloadAnchor.remove();
                this.showToast('Базу даних успішно експортовано!');
            }

            importDatabase(event) {
                const file = event.target.files[0];
                if (!file) return;

                const reader = new FileReader();
                reader.onload = (e) => {
                    try {
                        const importedData = JSON.parse(e.target.result);
                        if (typeof importedData === 'object' && importedData !== null) {
                            this.articles = { ...this.articles, ...importedData };
                            this.saveArticles();
                            this.showToast('Базу даних успішно відновлено з JSON!');
                            this.goHome();
                        } else {
                            this.showToast('Некоректний формат файлу!', 'error');
                        }
                    } catch (err) {
                        this.showToast('Помилка зчитування JSON-файлу', 'error');
                    }
                };
                reader.readAsText(file);
                event.target.value = ''; // Reset input
            }

            confirmResetAll() {
                this.openModal({
                    title: 'Очистити всі дані?',
                    message: 'Ця дія вилучить УСІ ваші створені статті без можливості відновлення. Бажаєте продовжити?',
                    icon: 'fa-triangle-exclamation',
                    iconClass: 'bg-red-100 text-red-600 dark:bg-red-950/50',
                    confirmText: 'Очистити все',
                    onConfirm: () => {
                        localStorage.removeItem(this.STORAGE_KEY);
                        this.articles = {};
                        this.ensureHomePageExists();
                        this.showToast('Базу даних повністю очищено');
                        this.goHome();
                    }
                });
            }

            /* --- ARTICLE CREATION HELPERS --- */
            openNewArticleModal() {
                this.openModal({
                    title: 'Створити нову статтю',
                    message: 'Введіть назву для нової статті у Вікіпедії:',
                    showInput: true,
                    confirmText: 'Далі',
                    onConfirm: (inputVal) => {
                        if (inputVal && inputVal.trim()) {
                            this.createNewArticleNamed(inputVal.trim());
                        }
                    }
                });
            }

            openCreateMissingArticleModal(title) {
                this.openModal({
                    title: 'Сторінка не існує',
                    message: `Сторінки «${title}» ще немає у вашій Вікіпедії. Бажаєте створити її зараз?`,
                    confirmText: 'Створити статтю',
                    onConfirm: () => {
                        this.createNewArticleNamed(title);
                    }
                });
            }

            createNewArticleNamed(title) {
                this.currentTitle = title;
                if (!this.articles[title]) {
                    this.articles[title] = {
                        title: title,
                        body: '',
                        infobox: { title: title, image: '', caption: '', data: [] },
                        createdAt: new Date().toISOString(),
                        updatedAt: new Date().toISOString()
                    };
                }
                this.switchTab('edit');
            }

            /* --- CUSTOM UI DIALOGS & TOASTS (NO alert/confirm) --- */
            openModal({ title, message, showInput = false, icon = 'fa-circle-info', iconClass = 'bg-blue-100 text-wikiblue', confirmText = 'Підтвердити', onConfirm }) {
                const modal = document.getElementById('customModal');
                document.getElementById('modalTitle').innerText = title;
                document.getElementById('modalMessage').innerText = message;
                
                const iconContainer = document.getElementById('modalIconContainer');
                iconContainer.className = `w-9 h-9 rounded-full flex items-center justify-center ${iconClass}`;
                document.getElementById('modalIcon').className = `fa-solid ${icon}`;

                const inputContainer = document.getElementById('modalCustomInputContainer');
                const modalInput = document.getElementById('modalInput');

                if (showInput) {
                    inputContainer.classList.remove('hidden');
                    modalInput.value = '';
                    setTimeout(() => modalInput.focus(), 100);
                } else {
                    inputContainer.classList.add('hidden');
                }

                document.getElementById('modalConfirmBtn').innerText = confirmText;

                this.modalCallback = () => {
                    const val = showInput ? modalInput.value : true;
                    if (onConfirm) onConfirm(val);
                };

                modal.classList.remove('hidden');
            }

            closeModal(confirmed) {
                const modal = document.getElementById('customModal');
                modal.classList.add('hidden');
                if (confirmed && this.modalCallback) {
                    this.modalCallback();
                }
                this.modalCallback = null;
            }

            showToast(message, type = 'success') {
                const toast = document.getElementById('toastNotification');
                const msg = document.getElementById('toastMessage');
                const icon = document.getElementById('toastIcon');

                msg.innerText = message;
                if (type === 'error') {
                    icon.className = 'fa-solid fa-circle-xmark text-red-400 dark:text-red-600';
                } else {
                    icon.className = 'fa-solid fa-circle-check text-emerald-400 dark:text-emerald-600';
                }

                toast.classList.remove('translate-y-20', 'opacity-0');
                setTimeout(() => {
                    toast.classList.add('translate-y-20', 'opacity-0');
                }, 3000);
            }

            escapeHtml(str) {
                if (!str) return '';
                return str.replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;").replace(/"/g, "&quot;").replace(/'/g, "&#039;");
            }
        }

        // Initialize App on load
        let app;
        window.addEventListener('DOMContentLoaded', () => {
            app = new WikiApp();
        });
    </script>
</body>
</html>
