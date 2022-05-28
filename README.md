# README

```
bundle exec derailed bundle:mem


TOP: 45.7031 MiB
  rails/all: 37.1406 MiB
    rails: 13.3906 MiB (Also required by: active_record/railtie, active_model/railtie, and 9 others)
      rails/application: 6.1094 MiB
        active_support/key_generator: 4.1719 MiB
          openssl: 4.1406 MiB (Also required by: active_support/message_verifier, active_support/message_encryptor, and 3 others)
            openssl.so: 2.125 MiB
            /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/3.1.0/openssl/ssl: 1.7188 MiB
              ipaddr: 0.5625 MiB (Also required by: active_support/core_ext/object/json, rails/application/configuration)
                socket: 0.4219 MiB (Also required by: /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/3.1.0/openssl/ssl, net/protocol)
        yaml: 0.8438 MiB (Also required by: active_support/encrypted_configuration, rails/secrets, and 5 others)
          psych: 0.8281 MiB
            /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/3.1.0/psych/visitors: 0.3906 MiB
        rails/engine: 0.5469 MiB
      active_support: 4.9531 MiB (Also required by: active_support/railtie, active_support/i18n_railtie, and 16 others)
        active_support/logger: 4.0313 MiB
          active_support/logger_silence: 4.0313 MiB
            active_support/logger_thread_safe_level: 4.0313 MiB (Also required by: active_support/logger)
              concurrent: 4.0313 MiB (Also required by: /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/tzinfo-2.0.4/lib/tzinfo/string_deduper, /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/tzinfo-2.0.4/lib/tzinfo/data_source, and 3 others)
                concurrent/executors: 0.8906 MiB
                  concurrent/executor/timer_set: 0.4375 MiB
                concurrent/promises: 0.8594 MiB
                concurrent/atomics: 0.4375 MiB (Also required by: concurrent/executor/simple_executor_service)
                concurrent/set: 0.3438 MiB
        active_support/dependencies/autoload: 0.8125 MiB
          active_support/inflector/methods: 0.7969 MiB (Also required by: active_support/inflector, active_support/core_ext/string/inflections, and 3 others)
            active_support/inflections: 0.75 MiB (Also required by: active_support/inflector)
              active_support/inflector/inflections: 0.7344 MiB (Also required by: active_support/inflector)
                active_support/i18n: 0.5313 MiB (Also required by: active_support/inflector/transliterate, abstract_controller)
                  i18n: 0.3906 MiB
                    i18n/exceptions: 0.3125 MiB
                      cgi: 0.3125 MiB (Also required by: active_support/core_ext/object/to_query, /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/loofah-2.18.0/lib/loofah/html5/scrub, and 3 others)
      active_support/railtie: 1.9063 MiB
        active_support/i18n_railtie: 1.8906 MiB
          rails/railtie/configuration: 1.8438 MiB (Also required by: rails/engine/configuration)
            rails/configuration: 1.8125 MiB
              active_support/core_ext/object: 1.7969 MiB
                active_support/core_ext/object/json: 1.6563 MiB (Also required by: active_support/json/encoding)
                  active_support/core_ext/time/conversions: 0.875 MiB (Also required by: active_support/core_ext/date_time/conversions, active_support/core_ext/time/calculations)
                    active_support/values/time_zone: 0.875 MiB (Also required by: active_support/core_ext/date_time/conversions, active_support/time_with_zone)
                      tzinfo: 0.75 MiB
                        /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/tzinfo-2.0.4/lib/tzinfo/with_offset: 0.5313 MiB
                  uri/generic: 0.4063 MiB (Also required by: global_id/uri/gid)
                  json: 0.3438 MiB (Also required by: sprockets/bower, sprockets/npm, and 5 others)
      action_dispatch/railtie: 0.3438 MiB (Also required by: action_controller/railtie)
        action_dispatch: 0.3125 MiB (Also required by: action_controller, active_storage/service)
    action_mailbox/engine: 12.7656 MiB
      action_mailbox: 12.7656 MiB
        action_mailbox/mail_ext: 12.7344 MiB
          action_mailbox/mail_ext/address_equality.rb: 12.1563 MiB
            mail/elements/address: 12.1406 MiB
              mail/parsers/address_lists_parser: 12.1406 MiB (Also required by: mail/parsers)
                mail/parsers: 2.3438 MiB
                  mail/parsers/received_parser: 2.0469 MiB
          mail: 0.5781 MiB
    active_record/railtie: 4.7969 MiB (Also required by: active_storage/engine, action_mailbox/engine)
      active_record: 2.625 MiB (Also required by: active_storage, /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/rails_event_store_active_record-2.4.1/lib/rails_event_store_active_record/event)
        active_record/errors: 1.3125 MiB
          active_model/errors: 1.2656 MiB
        arel: 1.1094 MiB
          arel/nodes: 0.5313 MiB
          arel/visitors: 0.3594 MiB
      action_controller/railtie: 2.0781 MiB (Also required by: active_storage/engine, rails/all, and 3 others)
        action_controller: 1.4063 MiB
          action_controller/metal/strong_parameters: 1.1719 MiB
            rack/test: 0.9531 MiB
              rack/test/cookie_jar: 0.4063 MiB
                rack/utils: 0.3594 MiB (Also required by: sprockets/server, sprockets/context)
        action_view/railtie: 0.5938 MiB (Also required by: rails/all)
          action_view: 0.5469 MiB (Also required by: sprockets/rails/helper)
            active_support/core_ext/string/output_safety: 0.4219 MiB (Also required by: action_view/helpers/capture_helper, action_view/helpers/output_safety_helper, and 6 others)
    active_storage/engine: 3.7969 MiB (Also required by: action_mailbox/engine, action_text/engine)
      active_storage: 2.0938 MiB
        marcel: 1.9531 MiB
          marcel/magic: 1.9375 MiB
            marcel/tables: 1.8906 MiB
      active_job/railtie: 1.4063 MiB (Also required by: action_mailer/railtie, rails/all)
        global_id/railtie: 1.3125 MiB
          active_support/core_ext/integer/time: 1.1563 MiB (Also required by: active_support/time)
            active_support/core_ext/numeric/time: 0.9688 MiB (Also required by: active_storage, active_support/time)
              active_support/core_ext/time/calculations: 0.9219 MiB (Also required by: active_support/file_update_checker, active_support/core_ext/time)
    action_text/engine: 1.9219 MiB
      action_text: 1.875 MiB
        nokogiri: 1.8438 MiB (Also required by: loofah)
          /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/extension: 0.5781 MiB (Also required by: /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/version/info)
            /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/3.1/nokogiri: 0.5781 MiB
          /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/xml: 0.5313 MiB
          /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/html4: 0.3281 MiB (Also required by: /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/nokogiri-1.13.6-arm64-darwin/lib/nokogiri/html)
    rails/test_unit/railtie: 0.3906 MiB
      rails/test_unit/line_filtering: 0.3906 MiB
        rails/test_unit/runner: 0.3906 MiB
          rake/file_list: 0.3125 MiB
  rails_event_store: 6.6406 MiB
    rails_event_store_active_record: 5.2656 MiB
      /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/rails_event_store_active_record-2.4.1/lib/rails_event_store_active_record/event: 5.2188 MiB
        active_record/base: 4.2656 MiB
          active_record/validations: 0.7188 MiB
            active_model/validations: 0.5625 MiB
          active_record/encryption: 0.5 MiB
          active_record/enum: 0.4063 MiB
            active_record/type: 0.3594 MiB
          active_record/querying: 0.3281 MiB
        active_record/relation: 0.4688 MiB
        active_record/associations/collection_proxy: 0.4688 MiB
    /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/rails_event_store-2.4.1/lib/rails_event_store/all: 1.375 MiB
      /Users/mostlyobvious/.rubies/ruby-3.1.2/lib/ruby/gems/3.1.0/gems/rails_event_store-2.4.1/lib/rails_event_store/browser: 0.9844 MiB
        ruby_event_store/browser/app: 0.9844 MiB
          sinatra/base: 0.8594 MiB
  sprockets/rails: 1.4688 MiB
    sprockets/railtie: 1.4688 MiB
      sprockets: 1.0781 MiB (Also required by: sprockets/rails/context, sprockets/rails/helper)
        sprockets/environment: 0.7188 MiB
          sprockets/base: 0.7188 MiB (Also required by: sprockets/cached_environment)
            sprockets/configuration: 0.4531 MiB (Also required by: sprockets)
      sprockets/rails/context: 0.3281 MiB
        action_view/helpers: 0.3281 MiB
  sqlite3: 0.3125 MiB
```
