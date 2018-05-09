
                <!DOCTYPE html>
                <!--[if lt IE 7]><html class="no-js lt-ie9 lt-ie8 lt-ie7"><![endif]-->
                <!--[if IE 7]><html class="no-js lt-ie9 lt-ie8"><![endif]-->
                <!--[if IE 8]><html class="no-js lt-ie9"><![endif]-->
                <!--[if gt IE 8]><!--><html lang="en" dir="ltr" class="client-nojs"><!--<![endif]-->
                <head>
                    <meta charset="UTF-8"/>
                    <link rel="stylesheet" href="https://s3.amazonaws.com/simple-gdi-doc/docs/resources/docs_splunk_com.css" />
                    <style>
                        #body-details #main-body ol li {
                            color: #000000;
                            font-weight: normal;
                        }

                        #body-details #main-body ul li {
                            color: #000000;
                        }
                    </style>
                    <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
                </head>
                <body style="padding: 20px">
                    <section id="detail-page"><div class="container" id="body-details-container"><div class="row" id="body-details"><div id="main-body">
                <h1>Create CloudTrail</h1>
<p>Testing x y
1. Sign in to the AWS Management Console and open the <a target="_blank" target="_blank" href="https://console.aws.amazon.com/">Cloudtrail console</a>. 
2. Choose the region where you want the trail to be created.
3. Choose <strong>Get Started Now</strong>.
4. On the <strong>Create Trail</strong> page, for <strong>Trail name</strong>, type a name for your trail. For more information, see <a href="https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-trail-naming-requirements.html">CloudTrail Trail Naming Requirements</a>.
5. For <strong>Apply trail to all regions</strong>, choose <strong>Yes</strong> to receive log files from all regions. This is the default and recommended setting. If you choose <strong>No</strong>, the trail logs files only from the region in which you create the trail.
6. For <strong>Management events</strong>, for <strong>Read/Write events</strong>, choose if you want your trail to log <strong>All</strong>, <strong>Read-only</strong>, <strong>Write-only</strong>, or <strong>None</strong>, and then choose <strong>Save</strong>. By default, trails log all management events. For more information, see <a href="https://docs.aws.amazon.com/awscloudtrail/latest/userguide/logging-management-and-data-events-with-cloudtrail.html#logging-management-events">Management Events</a>.
7. For <strong>Storage location</strong>, for <strong>Create a new S3 bucket</strong>, choose <strong>Yes</strong> to create a bucket. When you create a bucket, CloudTrail creates and applies the required bucket policies.</p>
<p>Note: If you choose No, choose an existing S3 bucket. The bucket policy must grant CloudTrail permission to write to it. For information about manually editing the bucket policy, see <a href="https://docs.aws.amazon.com/awscloudtrail/latest/userguide/create-s3-bucket-policy-for-cloudtrail.html">Amazon S3 Bucket Policy for CloudTrail</a>.</p>
<ol>
<li>
<p>For <strong>S3 bucket</strong>, type a name for the bucket you want to designate for log file storage. The name must be globally unique. For more information, see <a href="https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-s3-bucket-naming-requirements.html">Amazon S3 Bucket Naming Requirements</a>.</p>
</li>
<li>
<p>(Optional) Configure advanced settings for your trail. </p>
<ul>
<li>For <strong>Storage location</strong>, choose <strong>Advanced</strong>.</li>
<li>In the Log file prefix field, type a prefix for your Amazon S3 bucket. THe prefix is an addition to the URL for an Amazon S3 object that creates a folder-like organization in your bucket. The location where your log files will be stored appears under the text field.</li>
<li>For <strong>Encrypt log files</strong>,  choose <strong>Yes</strong> if you want AWS KMS to encrypt your log files.</li>
<li>For <strong>Create a new KMS key</strong>, choose <strong>Yes</strong> to create a key or <strong>No</strong> to use an existing one.</li>
<li>If you chose Yes, type an alias in the KMS key field. CloudTrail encrypts your log files with the key and adds the policy for you. </li>
</ul>
</li>
<li>
<p>Choose <strong>Create</strong>.</p>
</li>
<li>The new trail appears on the Trails page. The Trails page shows the trails in your account from all regions. In about 15 minutes, CloudTrail publishes log files that show the AWS API calls made in your account. You can see the log files in the S3 bucket that you specified.</li>
</ol>
                    </div></div></div></div>
                </body>
                </html>
                
