---
title: OpenGL
localeTitle: برنامج OpenGL
---
## تطوير اللعبة مع برنامج OpenGL

Open Graphics Library (OpenGL) هي واجهة برمجة تطبيقية مشتركة بين عدة لغات (API) لتقديم رسومات متجه ثنائية الأبعاد وثلاثية الأبعاد. يتم استخدام واجهة برمجة التطبيقات (API) عادةً للتفاعل مع وحدة معالجة الرسومات (GPU) ، لتحقيق عرض مسرّع للأجهزة.

بدأت شركة Silicon Graphics Inc (SGI) في تطوير OpenGL في عام 1991 وتم إصدارها في يناير 1992 ؛ تستخدم التطبيقات على نطاق واسع في مجالات التصميم بمساعدة الكمبيوتر (CAD) ، والواقع الافتراضي ، والتصور العلمي ، وتصور المعلومات ، ومحاكاة الطيران ، وألعاب الفيديو. منذ عام 2006 تم إدارة OpenGL من قبل مجموعة شركات خرنوس غير الربحية للتكنولوجيا.

## تطبيقات

يعد تطبيق Mesa 3D تطبيقًا مفتوح المصدر لـ OpenGL. يمكن أن يقدم عرضًا محضًا للبرامج ، وقد يستخدم أيضًا تسريع الأجهزة على BSD و Linux وغير ذلك من الأنظمة الأساسية من خلال الاستفادة من البنية الأساسية للعرض المباشر. اعتبارًا من الإصدار 13.0 ، يتم تطبيق الإصدار 4.5 من OpenGL القياسي.

## المتطلبات الأساسية

هناك حاجة إلى أي شرط مسبق خاص لمتابعة معظم البرامج التعليمية. الخبرة في أي لغة برمجة (C، Java، Lisp، Javascript) هي أفضل لفهم الأكواد بشكل كامل ، ولكن ليس هناك حاجة إليها ؛ سيكون الأمر أكثر تعقيدًا فقط لتعلم شيئين في نفس الوقت.

## تثبيت OpenGL على لينكس

ميسا هي مكتبة GL المستخدمة. يتضمن Ubuntu 16.04 Mesa 11.2 الذي يدعم OpenGL 4.1. فقط قم بتثبيت `libgl1-mesa-dev` و `mesa-common-dev` لتثبيت ملفات التطوير الخاصة به.

إذا كنت تحتاج بالفعل إلى 4.5 ، فستحتاج على الأرجح إلى التطوير ضد برامج AMD أو NVidia ، وستحتاج إلى بطاقة تدعم بالفعل 4.5 لتشغيل أي برنامج تقوم بإنشائه باستخدام هذا الإصدار من API.

#### معلومات اكثر:

[OpenGL Wiki](https://en.wikipedia.org/wiki/OpenGL) [دروس OpenGL](http://www.opengl-tutorial.org/)