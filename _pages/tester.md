---
layout: page-2
title: tester
include_in_header: no
---

<div class="features">

    <div class="feature">
        <div>
            <span class="fa-stack fa-1x">
                [<img src="https://raw.githubusercontent.com/cambragol/Fallout-Sonora/main/assets/Screen%20Shot%20Sonora.png" width="300" />](https://github.com/cambragol/Fallout-Sonora-English/releases/download/0.9.9/sonora_eng.zip "sonora_eng.zip")
            </span>
        </div>
        <div class="featureText">
        
            <h3>
                {{ feature.title }}
            </h3>
            <p>
                {{ feature.description }}
            </p>
        </div>
    </div>

      <div class="feature">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-{{ feature.fontawesome_icon_name }} fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                {{ feature.title }}
            </h3>
            <p>
                {{ feature.description }}
            </p>
        </div>
    </div>

      <div class="feature">
        <div>
            <span class="fa-stack fa-1x">
                <i class="iconBack fas fa-circle fa-stack-2x"></i>
                <i class="iconTop fas fa-{{ feature.fontawesome_icon_name }} fa-stack-1x"></i>
            </span>
        </div>
        <div class="featureText">
            <h3>
                {{ feature.title }}
            </h3>
            <p>
                {{ feature.description }}
            </p>
        </div>
    </div>

</div>

