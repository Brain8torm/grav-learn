---
title: Что такое Grav?
taxonomy:
    category: docs
---

Grav - это **быстрая**, **простая** и  **гибкая** CMS на файлах. Она требует **ноль** действий для установки. Просто распакуйти ZIP-архив, и вы уже в деле. Несмотря на то, что Grav следует принципам, аналогичным другим файловым CMS, у него в отличие от многих другая философия разработки.

Название **Grav** - это сокращенная версия от слова **Gravity** (от англ. *гравитация*). Общее пространство имен нашей платформы и фильма с Сандрой Буллок в главной роли - чистое совпадение! Что еще более важно, гравитация также является фундаментальным физическим принципом, описывающим силы притяжения между объектами. Откровенно говоря, название было выбрано как временное "кодовое имя" для проекта, и оно просто прижилось.

Базовая архитектура Grav построена с использованием хорошо зарекомендовавших себя и _лучших в своем классе_ технологий. Это сделано для того, чтобы Grav был прост в использовании и легко расширялся Некоторые из этих ключевых технологий включают в себя:

* [Шаблонизатор Twig](https://twig.symfony.com/): для мощного управления пользовательским интерфейсом
* [Markdown](https://en.wikipedia.org/wiki/Markdown): для простого создания контента
* [YAML](https://yaml.org): для простоты конфигурации
* [Parsedown](https://parsedown.org/): для поддержки Markdown и Markdown Extra
* [Doctrine Cache](https://www.doctrine-project.org/projects/doctrine-orm/en/2.6/reference/caching.html): для производительности
* [Pimple Dependency Injection Container](https://github.com/silexphp/Pimple): для расширяемости и поддержки
* [Symfony Event Dispatcher](https://symfony.com/doc/current/components/event_dispatcher.html): для обработки событий плагинов
* [Symfony Console](https://symfony.com/doc/current/components/console.html): для консольного интерфейса
* [Gregwar Image Library](https://github.com/Gregwar/Image): для динамической обработки изображений

## Место Grav во вселенной

Существует множество мощных CMS с открытым исходным кодом для создания сложных сайтов.  Одни из часто используемых - [Joomla](https://www.joomla.org), [WordPress](https://wordpress.org), и [Drupal](https://www.drupal.org). Недостатком этих платформ является сложная кривая обучения. Это требует значительных затрат времени, а это может быть время, которого у вас нет.

Данные платформы предоставляют множество особенностей и функций, которые вы можете расширить с помощью широкого спектра плагинов и тем, как с открытым исходным кодом, так и проприетарных. Эти расширения и темы сами по себе зачастую снабжены множеством функций, что требует от разработчика больше знаний и времени.

In the end, you often find yourself creating a website that requires many plugins and extensions from many different vendors. This can make your design overly complicated and difficult to maintain over the long term.

Grav tackles the problem differently.  It focuses primarily on your content and turns your content structure into a navigable site.  The underpinnings of Grav are simple, yet via extensive **events**, you have complete control over every step in the Grav workflow.

This solution allows simple plugins to quickly and easily add powerful functionality. Using **Grav** also leads to a rapid development environment with an installation process that takes seconds, including a straightforward content creation method with a minimal learning curve. All of this contributes to making Grav friendly to the designer, the developer, and the end user.

To get a basic site up-and-running requires minimal Web development experience. If you dig a little deeper, you will discover that there is very little Grav cannot accomplish.

### Grav Logos and Press Information

You can find a summary about Grav, including **Grav logos** and **press information**, on our [media page](https://getgrav.org/media).

!!! The simplest way to navigate the documentation is to use the **Previous** and **Next** arrows (<i class="fa fa-angle-left"></i> | <i class="fa fa-angle-right"></i>) at the top of each page. You can see your progress represented by the check marks (<i class="fa fa-check-circle"></i>) in the sidebar.
