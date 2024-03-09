<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建大型语言模型（从头开始）</font></font></h1><a id="user-content-build-a-large-language-model-from-scratch" class="anchor" aria-label="永久链接：构建大型语言模型（从头开始）" href="#build-a-large-language-model-from-scratch"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该存储库包含用于编码、预训练和微调类似 GPT 的 LLM 的代码，并且是《</font></font><a href="http://mng.bz/orYv" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建大型语言模型（从头开始）》</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">一书的官方代码存储库。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（如果您从 Manning 网站下载了代码包，请考虑访问 GitHub 上的官方代码存储库：</font></font><a href="https://github.com/rasbt/LLMs-from-scratch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/rasbt/LLMs-from-scratch</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。）</font></font></p>
<br>
<br>
<p dir="auto"><a href="http://mng.bz/orYv" rel="nofollow"><img src="/rasbt/LLMs-from-scratch/raw/main/images/cover.jpg" width="250px" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在</font></font><a href="http://mng.bz/orYv" rel="nofollow"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建大型语言模型（从头开始）</font></font></em></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中，您将发现法学硕士如何从内到外地工作。</font><font style="vertical-align: inherit;">在本书中，我将逐步指导您创建自己的法学硕士，并用清晰的文本、图表和示例解释每个阶段。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">本书中描述的用于出于教育目的训练和开发您自己的小型但实用的模型的方法反映了创建大型基础模型（例如 ChatGPT 背后的模型）所使用的方法。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">链接到官方</font></font><a href="https://github.com/rasbt/LLMs-from-scratch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">源代码库</font></font></a></li>
<li><a href="http://mng.bz/orYv" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">曼宁</font><a href="http://mng.bz/orYv" rel="nofollow"><font style="vertical-align: inherit;">早期访问版本的链接</font></a></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">国际标准书号 9781633437166</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预计 2025 年初出版</font></font></li>
</ul>
<br>
<br>
<div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">目录</font></font></h1><a id="user-content-table-of-contents" class="anchor" aria-label="固定链接：目录" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，该</font></font><code>Readme.md</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件是 Markdown ( </font></font><code>.md</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">) 文件。</font><font style="vertical-align: inherit;">如果您已从 Manning 网站下载了此代码包并在本地计算机上查看它，我建议您使用 Markdown 编辑器或预览器进行正确查看。</font><font style="vertical-align: inherit;">如果您还没有安装 Markdown 编辑器，</font></font><a href="https://www.marktext.cc" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">MarkText</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">是一个不错的免费选择。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者，您可以在 GitHub 上查看此文件和其他文件：</font></font><a href="https://github.com/rasbt/LLMs-from-scratch"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/rasbt/LLMs-from-scratch</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<br>
<br>
<table>
<thead>
<tr>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">章节标题</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">主代码（用于快速访问）</font></font></th>
<th><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有代码+补充</font></font></th>
</tr>
</thead>
<tbody>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 1 章：理解大型语言模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无代码</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无代码</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 2 章：使用文本数据</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch02/01_main-chapter-code/ch02.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ch02.ipynb</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch02/01_main-chapter-code/dataloader.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">dataloader.ipynb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（摘要）</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-exercise </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch02/01_main-chapter-code/exercise-solutions.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-solutions.ipynb</font></font></a></td>
<td><a href="/rasbt/LLMs-from-scratch/blob/main/ch02"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">./ch02</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 3 章：编码注意力机制</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch03/01_main-chapter-code/ch03.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ch03.ipynb</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> -</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch03/01_main-chapter-code/multihead-attention.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多头注意力.ipynb</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（摘要）</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch03/01_main-chapter-code/exercise-solutions.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">练习解决方案.ipynb</font></font></a></td>
<td><a href="/rasbt/LLMs-from-scratch/blob/main/ch03"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">./ch03</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 4 章：从头开始实现 GPT 模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch04/01_main-chapter-code/ch04.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ch04.ipynb</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch04/01_main-chapter-code/gpt.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">gpt.py</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（摘要）</font></font><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/ch04/01_main-chapter-code/exercise-solutions.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">练习解决方案.ipynb</font></font></a></td>
<td><a href="/rasbt/LLMs-from-scratch/blob/main/ch04"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">./ch04</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 5 章：未标记数据的预训练</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年第一季度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 6 章：文本分类微调</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年第二季度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 7 章：利用人工反馈进行微调</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年第二季度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">第 8 章：在实践中使用大型语言模型</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2024 年第 2/3 季度</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...</font></font></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附录 A：PyTorch 简介</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/03_main-chapter-code/code-part1.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码部分1.ipynb</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> -</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/03_main-chapter-code/code-part2.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码部分2.ipynb</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - </font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/03_main-chapter-code/DDP-script.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">DDP-script.py</font></font></a><br><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> -</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/03_main-chapter-code/exercise-solutions.ipynb"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">练习解决方案.ipynb</font></font></a></td>
<td><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">./附录-A</font></font></a></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附录 B：参考资料和进一步阅读</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无代码</font></font></td>
<td></td>
</tr>
<tr>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">附录 C：练习</font></font></td>
<td><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无代码</font></font></td>
<td></td>
</tr>
</tbody>
</table>
<br>
<div class="markdown-alert markdown-alert-tip" dir="auto"><p class="markdown-alert-title" dir="auto"><svg class="octicon octicon-light-bulb mr-2" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="M8 1.5c-2.363 0-4 1.69-4 3.75 0 .984.424 1.625.984 2.304l.214.253c.223.264.47.556.673.848.284.411.537.896.621 1.49a.75.75 0 0 1-1.484.211c-.04-.282-.163-.547-.37-.847a8.456 8.456 0 0 0-.542-.68c-.084-.1-.173-.205-.268-.32C3.201 7.75 2.5 6.766 2.5 5.25 2.5 2.31 4.863 0 8 0s5.5 2.31 5.5 5.25c0 1.516-.701 2.5-1.328 3.259-.095.115-.184.22-.268.319-.207.245-.383.453-.541.681-.208.3-.33.565-.37.847a.751.751 0 0 1-1.485-.212c.084-.593.337-1.078.621-1.489.203-.292.45-.584.673-.848.075-.088.147-.173.213-.253.561-.679.985-1.32.985-2.304 0-2.06-1.637-3.75-4-3.75ZM5.75 12h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5ZM6 15.25a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75Z"></path></svg><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提示</font></font></p><p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您需要有关安装 Python 和 Python 包的更多指导，</font><font style="vertical-align: inherit;">请参阅</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/01_optional-python-setup-preferences"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文件夹和</font></font><a href="/rasbt/LLMs-from-scratch/blob/main/appendix-A/02_installing-python-libraries"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此文件夹。</font></font></a><font style="vertical-align: inherit;"></font></p>
</div>
<br>
<br>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下面显示的是一个心理模型，总结了本书所涵盖的内容。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/rasbt/LLMs-from-scratch/blob/main/images/mental-model.jpg"><img src="/rasbt/LLMs-from-scratch/raw/main/images/mental-model.jpg" width="600px" style="max-width: 100%;"></a></p>
</article></div>
