## Usage

import { KeycloakAdminClient } from '@s3pweb/keycloak-admin-client-cjs';

@Injectable()
export class KeycloakService {
    private readonly kcAdminClient: KeycloakAdminClient;

    constructor(logger: LoggingService) {
        this.log = logger.getLogger(KeycloackService.name);
        this.kcAdminClient = new KeycloakAdminClient();
    }

}
```
