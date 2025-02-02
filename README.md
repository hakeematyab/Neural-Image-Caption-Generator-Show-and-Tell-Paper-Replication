<!-- PROJECT LOGO -->
<div align="center">
  <a href="[https://github.com/hakeematyab/Neural-Image-Caption-Generator-Show-and-Tell-Paper-Replication](https://github.com/hakeematyab/Neural-Image-Caption-Generator-Show-and-Tell-Paper-Replication)">
    <img src="https://github.com/hakeematyab/AuthentiFeel/assets/88573121/aaed46bd-c47a-4e92-b6e2-f7c067ab13bd" alt="Logo" width="896" height="512">
  </a>
</div>

# Show and Tell: A Neural Image Caption Generator - Paper Replication
Vinyals, Oriol, et al. "Show and tell: A neural image caption generator." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.

# 

<!-- RESULTS -->
## Results

<table>
  <tr>
    <td><strong>Image</strong></td>
    <td><strong>Captions</strong></td>
  </tr>
  <tr>
    <td>
      <strong>Example 1</strong><br>
      <img src="https://github.com/hakeematyab/Neural-Image-Caption-Generator-Show-and-Tell-Paper-Replication/assets/88573121/3d83fe70-89d8-468a-84d8-31b7fe24fe62" alt="Example 1 Image" width="300"/>
    </td>
    <td>
      <strong>Actual Caption:</strong> <code>&lt;start&gt; &lt;oov&gt; &lt;oov&gt; to &lt;oov&gt; the image above &lt;end&gt; &lt;oov&gt;</code><br>
      <strong>Output Caption:</strong> <code>&lt;start&gt; cat laying on top of laptop &lt;end&gt;</code>
    </td>
  </tr>
  <tr>
    <td>
      <strong>Example 2</strong><br>
      <img src="https://github.com/hakeematyab/Neural-Image-Caption-Generator-Show-and-Tell-Paper-Replication/assets/88573121/03009b1a-65ec-48f3-8c1d-d63d56714263" alt="Example 2 Image" width="300"/>
    </td>
    <td>
      <strong>Actual Caption:</strong> <code>&lt;start&gt; &lt;oov&gt; &lt;oov&gt; slope near &lt;oov&gt; &lt;oov&gt; &lt;end&gt; &lt;oov&gt; &lt;oov&gt;</code><br>
      <strong>Output Caption:</strong> <code>&lt;start&gt; person that is skiing in the snow &lt;end&gt;</code>
    </td>
  </tr>
  <tr>
    <td>
      <strong>Example 3</strong><br>
      <img src="https://github.com/hakeematyab/Neural-Image-Caption-Generator-Show-and-Tell-Paper-Replication/assets/88573121/a1e3ddf9-404b-48d0-8239-5480599f0823" alt="Example 3 Image" width="300"/>
    </td>
    <td>
      <strong>Actual Caption:</strong> <code>&lt;start&gt; bus is parked at the bus &lt;oov&gt; &lt;end&gt; &lt;oov&gt;</code><br>
      <strong>Output Caption:</strong> <code>&lt;start&gt; large red bus on city street &lt;end&gt;</code>
    </td>
  </tr>
</table>

---

## Metrics

The performance of the model was evaluated using standard metric for image captioning tasks, the BLEU scores. Below are the results:

- **BLEU-1:** 44
- **BLEU-2:** 22
- **BLEU-4:** 9

These metrics indicate the effectiveness of the caption generator in producing relevant and accurate captions.


<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

<a href = "https://www.linkedin.com/in/hakeem-atyab/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href = "mailto: hakeem.at@northeastern.edu"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/hakeematyab" title="Hakeem Atyab on GitHub">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS 
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>-->



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo_name.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo_name/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo_name.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo_name/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo_name.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo_name/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo_name.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo_name/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo_name.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo_name/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Python-url]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
