## Directory layout

- [aws](aws)
  - [aws/aws_domain_redirect](aws/aws_domain_redirect)
  - [aws/aws_ec2_ebs_docker_host](aws/aws_ec2_ebs_docker_host)
    - resource aws_instance
    - resource aws_key_pair
    - resource aws_security_group
    - resource aws_security_group_rule
    - resource aws_volume_attachment
    - resource null_resource
  - [aws/aws_lambda_api](aws/aws_lambda_api)
    - resource aws_acm_certificate
    - resource aws_acm_certificate_validation
    - resource aws_api_gateway_base_path_mapping
    - resource aws_api_gateway_deployment
    - resource aws_api_gateway_domain_name
    - resource aws_api_gateway_integration
    - resource aws_api_gateway_integration_response
    - resource aws_api_gateway_method
    - resource aws_api_gateway_method_response
    - resource aws_api_gateway_method_settings
    - resource aws_api_gateway_resource
    - resource aws_api_gateway_rest_api
    - resource aws_api_gateway_stage
    - resource aws_iam_policy
    - resource aws_iam_role
    - resource aws_iam_role_policy_attachment
    - resource aws_lambda_function
    - resource aws_lambda_permission
    - resource aws_route53_record
  - [aws/aws_lambda_cronjob](aws/aws_lambda_cronjob)
    - resource aws_cloudwatch_event_rule
    - resource aws_cloudwatch_event_target
    - resource aws_iam_policy
    - resource aws_iam_role
    - resource aws_iam_role_policy_attachment
    - resource aws_lambda_function
    - resource aws_lambda_permission
  - [aws/aws_mailgun_domain](aws/aws_mailgun_domain)
    - resource aws_route53_record
    - resource mailgun_domain
  - [aws/aws_reverse_proxy](aws/aws_reverse_proxy)
    - resource aws_acm_certificate
    - resource aws_acm_certificate_validation
    - resource aws_cloudfront_distribution
    - resource aws_iam_policy
    - resource aws_iam_role
    - resource aws_iam_role_policy_attachment
    - resource aws_lambda_function
    - resource aws_route53_record
  - [aws/aws_static_site](aws/aws_static_site)
    - resource aws_s3_bucket
    - resource aws_s3_bucket_policy
    - resource random_string
  - [aws/aws_vpc_msk](aws/aws_vpc_msk)
    - resource aws_acmpca_certificate_authority
    - resource aws_cloudwatch_log_group
    - resource aws_eip
    - resource aws_iam_instance_profile
    - resource aws_iam_role
    - resource aws_iam_role_policy_attachment
    - resource aws_instance
    - resource aws_internet_gateway
    - resource aws_key_pair
    - resource aws_kms_alias
    - resource aws_kms_key
    - resource aws_msk_cluster
    - resource aws_msk_configuration
    - resource aws_nat_gateway
    - resource aws_route_table
    - resource aws_route_table_association
    - resource aws_security_group
    - resource aws_subnet
    - resource aws_vpc
    - resource random_id
    - resource random_uuid
  - [aws/static_website_ssl_cloudfront_private_s3](aws/static_website_ssl_cloudfront_private_s3)
    - resource aws_cloudfront_distribution
    - resource aws_cloudfront_origin_access_identity
    - resource aws_route53_record
    - resource aws_s3_bucket
    - resource aws_s3_bucket_policy
    - resource aws_s3_bucket_public_access_block
  - [aws/wordpress_fargate](aws/wordpress_fargate)
    - resource aws_appautoscaling_policy
    - resource aws_appautoscaling_target
    - resource aws_cloudfront_distribution
    - resource aws_cloudwatch_log_group
    - resource aws_cloudwatch_metric_alarm
    - resource aws_db_subnet_group
    - resource aws_ecs_cluster
    - resource aws_ecs_service
    - resource aws_ecs_task_definition
    - resource aws_efs_file_system
    - resource aws_efs_mount_target
    - resource aws_iam_policy
    - resource aws_iam_role
    - resource aws_iam_role_policy_attachment
    - resource aws_lb_listener_rule
    - resource aws_lb_target_group
    - resource aws_rds_cluster
    - resource aws_route53_record
    - resource aws_security_group
    - resource aws_ssm_parameter
    - resource random_string