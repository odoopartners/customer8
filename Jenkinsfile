@Library('test_shared_library')

def prod_deploy_name = "customer8-odoo15"

def odoo_version="15.0"

def dockerhub_repo_name = "customer8"

buildPipeline(stage:"prod",dockerhub_repo_name:"${dockerhub_repo_name}",prod_deploy_name:"${prod_deploy_name}",odoo_version:"${odoo_version}")
