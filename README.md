# Zyscythe 👋
![Image](https://github.com/user-attachments/assets/41fdb3d1-49d9-421a-8e3d-dd61f4aa2990)
<div align="center">
  <img height="200" src="/anime-girl.gif" alt="gif" />
</div>
Digital artist exploring the art of visual storytelling, with a focus on crafting compelling character designs and immersive game lore.


*   ## Design Tools
*   ![Canva](images/canva-icon.png) Canva
*   [![Pinterest](https://img.shields.io/badge/Pinterest-%23E60023.svg?style=for-the-badge&logo=pinterest&logoColor=white)](https://pin.it/1F60L5KeJ)

## Inspirations

*   [Punishing Gray Raven]: [We call it the Golden Age, the pinnacle of human civilization. We master quantum computing and cold fusion, climbing the noble ladder of progress, we reach for the stars themselves.]
*   [adalah Ryukishi07]: [About him, his masterpieces made me know what the true meaning of being human is.]

## Dream Projects

I aspire to be a story designer for RPGs or adventure games. I want to create stories about friendship, sacrifice, and self-discovery. My dream role is to focus on worldbuilding and character design.

path_parameters = {gem: "orange"}
query_parameters = {
  style: "flat",
  logo: "github",
  logoColor: "yellow",
  logoSize: "auto",
  label: "banana",
  labelColor: "blue",
  color: "black",
  cacheSeconds: "3600",
  link: "https://example.com/green/red",
}
Shields::Badge.gem_total_downloads(path_parameters:, query_parameters:)
# => "[![RubyGems Total Downloads](https://img.shields.io/gem/dt/orange?style=flat&logo=github&logoColor=yellow&logoSize=auto&label=banana&labelColor=blue&color=black&cacheSeconds=3600&link=https%3A%2F%2Fexample.com%2Fgreen%2Fred)](https://rubygems.org/gems/orange)

# And again it doesn't matter if the arguments are top-level or nested inside path and query parameters:
Shields::Badge.gem_total_downloads(**path_parameters, **query_parameters)
# => "[![RubyGems Total Downloads](https://img.shields.io/gem/dt/orange?style=flat&logo=github&logoColor=yellow&logoSize=auto&label=banana&labelColor=blue&color=black&cacheSeconds=3600&link=https%3A%2F%2Fexample.com%2Fgreen%2Fred)](https://rubygems.org/gems/orange)
