---
layout: page
title: Todo List
description: My first Project with Swfit and SwiftUI
img: assets/img/3.jpg
importance: 2
category: Swift
giscus_comments: true
---

To start learning Swift, for me it's a new programming language, I decided to create a Todo List App using Swift, and Firebase. Throughout this journey, I've picked up a lot of new skills and knowledge in programming with Swift and integrating Firebase for backend services.

At the beginning I have one choice to make that could change my whole journey. Do I want to start learning the new and modern SwiftUI Framework or do I want to learn the old UIKit Framework. I watched a bunch of videos to decide and here are some pros and cons for SwiftUI:

### **SwiftUI**

<table>
  <tr>
    <th>Pros</th>
    <th>&nbsp;&nbsp;Cons</th>
  </tr>
  <tr>
    <td>• Newer</td>
    <td>&nbsp;&nbsp;• Most old Apps still use UIKit</td>
  </tr>
  <tr>
    <td>• Preferred by Apple</td>
    <td>&nbsp;&nbsp;• Smaller community</td>
  </tr>
  <tr>
    <td>• Gets updates</td>
    <td>&nbsp;&nbsp;• Some advanced features may be missing</td>
  </tr>
</table>
<br>

Although UIKit is preferred by most companies, because most older apps still use it, I decided to learn SwiftUI.

As a Backend solution I intergrated Firebase. Firebase is a really good tool if you want to intergrade a authentification in you App and to store data.
Learning how to use these Services has given me the skills to build scalable and secure applications.

One of the biggest challenges I had to learn was making sure that the Database stayed consistent with the App and that the Authentification was working smothily.

As a code design pattern I used the MVVM (Model-View-ViewModel) architecture because it keeps my app organized and easier to manage and update. The Model handles the data, the view is all about user interface and the viewmodel acts like a bridge between them, making sure that changes in the data automatically reflectin the UI.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1_project/mvvm.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Overall this Project boosted my experience in Swift and also in my programming skills. It's a really good beginner app where you can learn the basics of a Programming Language (not only Swift)

:)

{% if site.data.repositories.1_project %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.1_project %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
