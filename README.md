# onanion.github.io

[ADVERTISEMENT]

**Home 728x90**
/_layouts/default.html
-penempatan
<!-- Site Logo/Name
    ================================================== -->
xxx
    <!-- Site Tag
    ================================================== -->
    {% if page.url == '/' %}
        <p class="sitetag">
<center>
<a href="#" target="_blank">
<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEj7t3p34bLv02do5hWhikN27RDdQ-bHCXDTPJDlI7XvmMdmsPe757kNilcJt7cgNSGg7BXS9-4bRtQ8cskWyl6zWmAvJQ-y7H2XzvPl83unFf5DXR9SFIzzXnZ8ddz3FMWVwpzMeA0kKDiPIkFhJweUdkTLPtQggS-dLkbRaDt47V9BNmDpMKbuLJI7/s1600/20220724_144458_0000.png" alt="adv">
</a>
</center>
        </p>
    {% endif %}

**Home 800x538**
/index.html
-penempatan
<!-- Posts Index
================================================== -->
<div class="blog-grid-container">
        <!-- begin adv 800x538 -->
<div class="blog-grid-item">
    <div class="card h-100">
        <div class="maxthumb">
            <a href="#" target="_blank">
                        <img class="img-thumb lazyimg" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjDJUjM17KlPXgFqkoZduOvW_LD46OPa-gw6czntHRaaF8ehMXuPHP0MnqMMEuPQpnlBAVKYX8Tf4-D1WeiLceOtpzck-BenXFsz3jF5ssMQDG9QIJ-0QS2G5N0bIj0ADvE20rua8iVa4PaoMcXA2v3HjjMGfzh7vcNAGH_ZSA0fM3risKW-WXtp08c/s1600/20220724_141840_0000.png" alt="800x538px">
            </a>
        </div>
        <div class="card-body">
            <h2 class="card-title">
                <a class="text-dark" href="/midv-133/">[ADVERTISEMENT]</a>
            </h2>
        </div>
    </div>
</div>
<!-- end adv 800x538-->
    {% for post in paginator.posts %}
        {% include postbox.html %}
    {% endfor %}
</div>

Contoh:

<img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEg3MpPPtvcSzTweIvFzluQRrYjRTwuKkqqAx3yNbYgZGtS5v4sP226wP9WH_yHGjfUvXibBUYjQ2ZM7fDTkoHcHAiDJS3hWNYLnLJlYvMF4IVdtMrCBS9yMk20He9mMERF2PonHnerIdQbD3iC6SHfcSymwutUE__3MXUqwFYPutohsv3XtDjm2hySC/s1600/IMG_20220724_150946.jpg">
