# portfolio
my portfolio


# plugins installed

hexo init

npm install -g hexagon-cli
%% https://github.com/adamsiwiec/hexagon
% The only use for this seems to be listing installed plugins... it can't remove packages

hexa -p hexo-filter-pathfix
%% https://github.com/wayou/hexo-filter-pathfix
% does not seem to work?

sudo npm uninstall hexo-filter-pathfix
sudo npm uninstall hexo-asset-path



%% https://github.com/r12f/hexo-asset-path
%  npm install hexo-asset-path --save

%% https://github.com/wayou/hexo-filter-pathfix
% UGH has to be of layout type "post"



% hexa -t next


%% https://hexo.io/api/filter.html#Execute-Filters


npm install --save hexo-featured-image

# themes

well... moving on for now...
git clone https://github.com/theme-next/hexo-theme-next themes/next


# Notes

Excerpt should not contain images above the "more" line. These images will not render properly in
the index view, due to relative path & asset folder issues


# to run

hexo clean; hexo gen -w
hexo s --debug
