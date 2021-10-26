
<p align="center"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=ErenDub&theme=onedark&margin-w=15&margin-h=15&column=7" alt="asyncfinkd" /></a> </p>

<div >
<img src="https://github-readme-stats.vercel.app/api?username=ErenDub&show_icons=true&theme=tokyonight&count_private=true" align="left"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ErenDub&layout=compact&theme=onedark&langs_count=15" align="right" height="150px"/>
<div>
- uses: Platane/snk@master
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # path of the generated gif file
    # If left empty, the gif file will not be generated
    gif_out_path: dist/github-snake.gif

    # path of the generated svg file
    # If left empty, the svg file will not be generated
    svg_out_path: dist/github-snake.svg
