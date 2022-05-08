Intentionally luring readers to click on a
certain content by exploiting their curiosity defines a
title as clickbait. Clickbait articles hide information or
distort the actual news to increase user interaction with
the articles. As this leads to quick spread of misinfor-
mation and lower the quality of web content, automatic
detection of clickbait titles is a very important task.
Although, several studies focused to detect clickbaits in
English articles, low resource language like Bangla has
not been given adequate attention. To tackle clickbait
titles in Bangla, we created an annotated dataset of
≈ 15K news articles and ≈ 65K unannotated news
articles which can be used to create supervised or semi-
supervised classification models. For the supervised ap-
proach, we ran a detailed comparison among traditional
linguistic feature based models, deep neural networks
and state of the art Transformer models. We also in-
vestigated whether semi-supervised learning approach
combined with Transformer networks trained with our
unannotated dataset can help improve the performance
of the system. Extensive experiments on these two
approaches show that semi-supervised approach does
not provide significant performance gain than its su-
pervised counterpart. We expect that this dataset and
the detailed analysis and comparison of these clickbait
detection systems will provide a fundamental basis
for future research into detecting clickbaits in Bengali
articles.
