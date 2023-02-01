---
layout: categories
title: "Nos activités"
---

{% for post in site.posts %}
                          <div class="container-fluid">
                            <div class="row justify-content-md-center">
                              <div class="col col-lg-10">
                                <li>
                                  <a href="{{ post.url }}">{{ post.title }}</a>
                                  {{ post.excerpt }}
                                </li>
                              </div>
                              <div class="col-md-auto">
                                <img src="{{ post.img }}" class="rounded">
                              </div>
                          </div>
                        </div>
{% endfor %}