自托管运行器可位于仓库、组织或{% ifversion fpt or ghec %}{% data variables.product.prodname_dotcom %} 上的企业帐户设置{% elsif ghes or ghae %}{% data variables.product.product_location %} 上的企业设置{% endif %}中。 要管理自托管运行器，您必须拥有以下权限，具体取决于添加自托管运行器的位置：
- **用户仓库**：您必须是仓库所有者。
- **组织**：您必须是组织所有者。
- **组织仓库**：您必须是组织所有者或者拥有该仓库的管理员权限。
{% ifversion ghec %}
- **企业账户**：您必须是企业所有者。
{% elsif ghes or ghae %}
- **企业**：您必须是 {% data variables.product.prodname_enterprise %} 站点管理员。
{% endif %}
