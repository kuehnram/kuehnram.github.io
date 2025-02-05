
# Survey on Rhetorical Figures
In this survey, we investigated over 40 papers that computationally detect lesser-known rhetorical figures beyond metaphor, irony, and sarcasm. During the research, we created a file containing all approaches with their details on models, language, performance scores, and many more.
You can expand the table by clicking on the symbol on the right in the bottom corner.

The tables are additional materials to the paper titled: 
**"Computational Approaches to the Detection of Lesser-Known Rhetorical Figures: A Systematic Survey and Research Challenges"**  with the authors **Ramona Kühn, Jelena Mitrović, and Michael Granitzer.** available on [arxiv](https://arxiv.org/abs/2406.16674)

Please cite
```
   @article{kuhn2024computational,
  title={Computational approaches to the detection of lesser-known rhetorical figures: A systematic survey and research challenges},
  author={K{\"u}hn, Ramona and Mitrovi{\'c}, Jelena and Granitzer, Michael},
  journal={arXiv preprint arXiv:2406.16674},
  year={2024}
}
```

This table gives an overview of the detection approaches:

<iframe width="402" height="346" frameborder="0" scrolling="no" src="https://onedrive.live.com/embed?resid=D0BAEAABFBD385B9%218706&authkey=%21AMBx9WpJzhqp7yo&em=2&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>

This table summarizes existing (annotated) datasets of rhetorical figures that we mentiond in the survey.

<table border="1">
    <thead>
        <tr>
            <th>Figurename</th>
            <th>Authors</th>
            <th>Language</th>
            <th>Sample Size</th>
            <th>Source/Context</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Alliteration</td>
            <td>--</td>
            <td>--</td>
            <td>--</td>
            <td>--</td>
        </tr>
        <tr>
            <td rowspan="3">Antimetabole</td>
            <td><cite>gawryjolek2009automated</cite></td>
            <td>??</td>
            <td>??</td>
            <td>??</td>
        </tr>
        <tr>
            <td><cite>java2015characterization</cite></td>
            <td>??</td>
            <td>25</td>
            <td>??</td>
        </tr>
        <tr>
            <td><cite>dubremetz2015rhetorical</cite></td>
            <td>English</td>
            <td>Available</td>
            <td>Fiction, scientific articles, quotes from websites</td>
        </tr>
        <tr>
            <td>Antithesis</td>
            <td><cite>zhu2022configure</cite></td>
            <td>Chinese</td>
            <td>250</td>
            <td>98 literary works (novels, prose)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>green2020towards</cite></td>
            <td>English</td>
            <td>120</td>
            <td>Extracted from <cite>dubremetz2015rhetorical</cite></td>
        </tr>
        <tr>
            <td></td>
            <td><cite>kuhn2023hidden</cite></td>
            <td>German</td>
            <td>??</td>
            <td>Telegram COVID-19 chats</td>
        </tr>
        <tr>
            <td>Euphemism</td>
            <td><cite>felt2020recognizing</cite></td>
            <td>English</td>
            <td>??</td>
            <td>List extension via Basilisk algorithm</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>gavidia2022cats</cite></td>
            <td>English</td>
            <td>??</td>
            <td>GloWbE Corpus, online sources</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>adewumi2021potential</cite></td>
            <td>??</td>
            <td>2384</td>
            <td>Idiomatic expressions dataset</td>
        </tr>
        <tr>
            <td>Hyperbole</td>
            <td><cite>troiano2018computational</cite></td>
            <td>English</td>
            <td>709</td>
            <td><span style="white-space: nowrap;">Web crawl and crowdsourcing (HYPO dataset)</span></td>
        </tr>
        <tr>
            <td></td>
            <td><cite>zhang2021mover</cite></td>
            <td>English</td>
            <td>17862</td>
            <td>HYPO dataset + online sources (HYPO-XL)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>zhu2022configure</cite></td>
            <td>Chinese</td>
            <td>690</td>
            <td>98 literary works (novels, prose)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>adewumi2021potential</cite></td>
            <td>??</td>
            <td>48</td>
            <td>Idiomatic expressions dataset</td>
        </tr>
        <tr>
            <td>Litotes</td>
            <td><cite>mukherjee2017negait</cite></td>
            <td>English</td>
            <td>??</td>
            <td>Wikipedia articles on diseases</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>yuan2017argumentative</cite></td>
            <td>Chinese</td>
            <td>100</td>
            <td>'The Analects of Confucius'</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>paida2019double</cite></td>
            <td>Chinese</td>
            <td>1360</td>
            <td>Extension of <cite>yuan2017argumentative</cite> dataset</td>
        </tr>
        <tr>
            <td>Meiosis</td>
            <td>--</td>
            <td>--</td>
            <td>--</td>
            <td>--</td>
        </tr>
        <tr>
            <td>Metonymy</td>
            <td><cite>zhu2022configure</cite></td>
            <td>Chinese</td>
            <td>603</td>
            <td>98 literary works (novels, prose)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>markert2007semeval</cite></td>
            <td>English</td>
            <td>??</td>
            <td>SemEval 2007 Shared Task 8</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>gritta2017vancouver</cite></td>
            <td>English</td>
            <td>??</td>
            <td>RELOCAR dataset (based on SemEval)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>zarcone2012logical</cite></td>
            <td>German</td>
            <td>??</td>
            <td>Online dataset</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>mathews2020large</cite></td>
            <td>English</td>
            <td>??</td>
            <td>WIMCOR (Wikipedia-based)</td>
        </tr>
        <tr>
            <td>Oxymoron</td>
            <td><cite>gawryjolek2009automated</cite></td>
            <td>??</td>
            <td>49</td>
            <td>??</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>java2015characterization</cite></td>
            <td>--</td>
            <td>--</td>
            <td>--</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>adewumi2021potential</cite></td>
            <td>??</td>
            <td>48</td>
            <td>Idiomatic expressions dataset</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>la2020oxymorons</cite></td>
            <td>Italian</td>
            <td>376</td>
            <td>Translated English antonym list</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>xu2023creative</cite></td>
            <td>English</td>
            <td>??</td>
            <td>Context-based interpretation (OCBI)</td>
        </tr>
        <tr>
            <td>Isocolon</td>
            <td><cite>gawryjolek2009automated</cite></td>
            <td>??</td>
            <td>62</td>
            <td>??</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>java2015characterization</cite></td>
            <td>??</td>
            <td>62</td>
            <td>??</td>
        </tr>
        <tr>
            <td>Parallelism</td>
            <td><cite>chen2021jointly</cite></td>
            <td>Chinese</td>
            <td>??</td>
            <td>Literature, textbooks, microblogs, websites</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>adewumi2021potential</cite></td>
            <td>??</td>
            <td>64</td>
            <td>Idiomatic expressions dataset</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>zhu2022configure</cite></td>
            <td>Chinese</td>
            <td>431</td>
            <td>98 literary works (novels, prose)</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>kuhn2023hidden</cite></td>
            <td>German</td>
            <td>??</td>
            <td>Telegram COVID-19 chats</td>
        </tr>
        <tr>
            <td>Polyptoton</td>
            <td><cite>gawryjolek2009automated</cite></td>
            <td>??</td>
            <td>??</td>
            <td>??</td>
        </tr>
        <tr>
            <td>Polysyndeton</td>
            <td><cite>gawryjolek2009automated</cite></td>
            <td>??</td>
            <td>28</td>
            <td>??</td>
        </tr>
        <tr>
            <td></td>
            <td><cite>java2015characterization</cite></td>
            <td>??</td>
            <td>62</td>
            <td>??</td>
        </tr>
        <tr>
            <td rowspan="3"><span style="white-space: nowrap;">Rhetorical<br>Questions</span></td>
            <td><cite>zhu2022configure</cite></td>
            <td>Chinese</td>
            <td>1185</td>
            <td>98 literary works (novels, prose)</td>
        </tr>
        <tr>
            <td><cite>chen2021jointly</cite></td>
            <td>Chinese</td>
            <td>??</td>
            <td>Literature, textbooks, microblogs, websites</td>
        </tr>
        <tr>
            <td><cite>morio2019revealing</cite></td>
            <td>??</td>
            <td>??</td>
            <td>Online forums, persuasive argumentation</td>
        </tr>
        <tr>
            <td>Zeugma</td>
            <td><cite>medkova2021building</cite></td>
            <td>Czech</td>
            <td>??</td>
            <td>??</td>
        </tr>
    </tbody>
</table>
